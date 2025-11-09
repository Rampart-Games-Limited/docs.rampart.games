# Reforger modding help

{% include "../../.gitbook/includes/armareforger.md" %}

{% stepper %}
{% step %}
### Turn off the server

**To avoid file curruption**&#x20;


{% endstep %}

{% step %}
### Find a mod



1. **Visit the Workshop**: [https://reforger.armaplatform.com/workshop](https://reforger.armaplatform.com/workshop)
{% endstep %}

{% step %}
### Getting Mod IDs

1. Find a mod you like the look of and click on it
2. The mod ID is in the Workshop page URL:

```
https://reforger.armaplatform.com/workshop/MOD_ID_HERE 
```
{% endstep %}

{% step %}
### Adding Mods

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
### Start the server&#x20;

Start the server and allow time for the mod install
{% endstep %}
{% endstepper %}



\
