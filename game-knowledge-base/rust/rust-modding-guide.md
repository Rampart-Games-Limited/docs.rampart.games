# Rust Modding Guide

<figure><img src="https://rampart.games/templates/lagom2/assets/img/page-manager/game-rust-art2.png" alt=""><figcaption></figcaption></figure>

{% stepper %}
{% step %}
Stop your Rust server

* Prevents corruption or conflicts while modifying server files.
{% endstep %}

{% step %}
Backup your server directory

*   Especially the following folders: \


    ```
    /oxide/RustDedicated_Data/server/
    ```
{% endstep %}

{% step %}
Install uMod (Oxide) on your server

1. Download the latest uMod build for Rust: [https://umod.org/download](https://umod.org/download)
2. Extract the contents into your Rust server root directory.
3. Overwrite existing files if prompted\
   \-  This installs the modding hooks and creates the /oxide/ folder.


{% endstep %}

{% step %}
Start the server.

* This generates essential folders:/oxide/plugins//oxide/config//oxide/data/
* Then stop the server again before adding plugins.
{% endstep %}

{% step %}
Download the desired server-side plugins.

* Use the official uMod site: https://umod.org/plugins
{% endstep %}

{% step %}
Install plugins.

Place all .cs plugin files into:/oxide/plugins
{% endstep %}

{% step %}
(Optional) Install plugin dependencies.

* Some plugins require specific libraries (e.g., VueLoader, ImageLibrary).
* Install those the same way: drop the .cs or .dll files into:/oxide/plugins/ or /oxide/plugins/libs/
{% endstep %}

{% step %}
Configure plugins (if needed)

1. Start the server once after adding the plugins.
2. Then stop it.
3. Config files will be auto-generated in:/oxide/config
4. Edit the .json files to customize settings for each plugin.


{% endstep %}

{% step %}
Restart the server.

1. Plugins will now load and run.
2. Check the console/logs for any loading errors.
{% endstep %}

{% step %}
Test your server.

1. Join your server and test the plugin features (e.g., teleportation, kits, economy).
2. You can now run the `oxide.reload PluginName` command in RCON to reload plugins without restarting.
{% endstep %}

{% step %}
(Optional) Use an RCON tool.

Tools like RustAdmin or BattleMetrics help manage the server and monitor plugin behavior remotely.
{% endstep %}

{% step %}
Keep your server updated.

* Each Rust update may break uMod.
* After each update:

&#x20;    \-  Reinstall the latest uMod build

&#x20;    \-  Check each plugin for compatibility or updates.\
\
[https://umod.org/download](https://umod.org/download)\
\
[https://umod.org/plugins?page=1\&sort=title\&sortdir=asc](https://umod.org/plugins?page=1\&sort=title\&sortdir=asc)




{% endstep %}
{% endstepper %}
