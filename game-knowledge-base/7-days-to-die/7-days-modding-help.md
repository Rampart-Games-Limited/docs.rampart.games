# 7 Days modding help

{% include "../../.gitbook/includes/7days.md" %}

{% stepper %}
{% step %}
### Stop Server

Stop your 7 Days to Die server.\
Prevents issues or corruption during mod installation.,
{% endstep %}

{% step %}
Backup your server.

Make a full backup of:\
\> Server install directory (especially /Data and /Mods),\
\> Save data (usually in /Saves or /Worlds),
{% endstep %}

{% step %}
Create a "Mods" folder in your server root directory (if it doesn’t exist).

Example path: `C:\7dtd-server\Mods`\
The structure should look like: `C:\7dtd-server\Mods[ModName][mod files]`,
{% endstep %}

{% step %}
Download server-side mods from a trusted source.

Recommended sites:\
[https://7daystodiemods.com/](https://7daystodiemods.com/)\
[https://community.7daystodie.com/forum/21-mods/](https://community.7daystodie.com/forum/21-mods/)
{% endstep %}

{% step %}
Extract each mod's contents into its own subfolder inside the Mods folder.

Each mod must have its own folder under /Mods,\
Example:C:\7dtd-server\Mods\ServerSideZombies\
→ should contain folders like /Config, /Harmony, /Scripts, etc.
{% endstep %}

{% step %}
(Optional) Ensure Harmony dependency is included.

Most server-side mods require Harmony.,\
Many mods include it; if not, install it separately:https://github.com/pardeike/Harmony
{% endstep %}

{% step %}
Start the server.

The game will automatically load any mods in the `/Mods` directory
{% endstep %}

{% step %}
Monitor logs for errors.

Use the log output or output\_log.txt to ensure all mods loaded correctly.,\
Errors may indicate missing files or incorrect folder structure.,
{% endstep %}

{% step %}
Test functionality in-game.

Join the server and verify that the mods are active.,\
Admin tools, zombie tweaks, or gameplay overhauls should be apparent.,
{% endstep %}

{% step %}
Maintain mod updates.

Revisit the mod source pages to download updates.,\
Always stop the server before replacing mod files.
{% endstep %}
{% endstepper %}
