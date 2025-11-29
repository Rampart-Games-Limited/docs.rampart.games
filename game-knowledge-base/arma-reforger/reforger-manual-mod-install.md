# Reforger Manual mod install

{% include "../../.gitbook/includes/armareforger.md" %}

{% stepper %}
{% step %}
### Turn off the server

**To avoid file curruption**&#x20;


{% endstep %}

{% step %}
#### Download Mod Locally

1. Subscribe to mod in Arma Reforger client
2. Launch game to trigger download
3. Find mod folder:
   * **Windows**: `%LOCALAPPDATA%\Arma Reforger\addons\`
   * **Linux**: `~/.local/share/bohemia/ArmaReforger/addons/`
{% endstep %}

{% step %}
### Transfer to Server

Copy the mod folder to your server:

**Server location**: `ServerProfile/Addons/MOD_ID_HERE/`

**Example**:

```
ServerProfile/
  Addons/
    5A5EA5882E11E9F0/  ← Enhanced Movement mod
      Addons/
      Configs/
      meta.conf
      gproj
```

```
https://reforger.armaplatform.com/workshop/MOD_ID_HERE 
```
{% endstep %}

{% step %}
#### Verify Installation

1. Check mod folder exists in correct location
2. Verify `meta.conf` file is present
3. Restart server
4. Check logs for successful mod loading

```
# Download mod locally first, then:
scp -r ~/.local/share/bohemia/ArmaReforger/addons/5A5EA5882E11E9F0 \
  user@server:/path/to/ServerProfile/Addons/
```
{% endstep %}

{% step %}
Add the mod ID to the Config.json file

```
{
  "bindPort": 2001,
  "publicPort": 2001,
  "game": {
    "name": "My Modded Server",
    "scenarioId": "{ECC61978EDCC2B5A}Missions/23_Campaign.conf",
    "maxPlayers": 32,
    "mods": [
      {
        "modId": "5A5EA5882E11E9F0",
        "name": "Enhanced Movement"
      },
      {
        "modId": "6B6FA6993F22F0A1",
        "name": "Radio Communication"
      }
    ]
  }
}
```
{% endstep %}

{% step %}
### Start the server

Start the server and allow time for the mod install
{% endstep %}
{% endstepper %}











<br>
