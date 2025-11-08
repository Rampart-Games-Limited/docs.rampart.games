# Ark modding help

{% include "../../.gitbook/includes/arkbanner.md" %}

{% stepper %}
{% step %}
Stop your ARK server.

* Prevents file corruption or crashes during mod changes.\

{% endstep %}

{% step %}
Back up your server directory.

Especially: ShooterGame/Saved/ and GameUserSettings.ini.
{% endstep %}

{% step %}
Download the mod using SteamCMD.\
Command: `steamcmd +login anonymous +workshop_download_item 346110 123456789 +quit`

* Replace 123456789 with the actual Mod ID
* This downloads to: steamapps/workshop/content/346110/123456789/
{% endstep %}

{% step %}
Locate the downloaded mod files.

* Inside: `steamapps/workshop/content/346110/123456789/`
* Look for folders like WindowsNoEditor or LinuxNoEditor, mod.info, modmeta.info, and possibly .z files.
{% endstep %}

{% step %}
Extract .z files (if any).

* Use a tool like Ark Mod Downloader or a z\_unpack script to decompress .z files into readable game assets.
{% endstep %}

{% step %}
Move the mod content to the ARK server.

* Copy the entire WindowsNoEditor (or LinuxNoEditor) folder content into:\
  ShooterGame/Content/Mods/123456789/
* Ensure it looks like:\
  ShooterGame/Content/Mods/123456789/ (mod files here)
* Also copy:123456789.mod → ShooterGame/Content/Mods/123456789.mod
* If the .mod file is missing, generate one using a script or mod manager.
{% endstep %}

{% step %}
Update your GameUserSettings.ini file.

* File path:\
  ShooterGame/Saved/Config/WindowsServer/GameUserSettings.ini
* Locate or create the ActiveMods= line and add your mod ID:\
  ActiveMods=123456789
* For multiple mods:\
  ActiveMods=123456789,987654321
{% endstep %}

{% step %}
(Optional) Add any required mod-specific configuration.

* Check the mod’s Steam Workshop page for any settings needed in:\
  Game.ini or GameUserSettings.ini.
{% endstep %}

{% step %}
Start your ARK server.

The mod will now load and initialize on startup.
{% endstep %}

{% step %}
Confirm the mod loaded successfully.

* Join your server and check if the mod content is available.
* Review server logs to see if the mod ID was parsed correctly.
{% endstep %}
{% endstepper %}
