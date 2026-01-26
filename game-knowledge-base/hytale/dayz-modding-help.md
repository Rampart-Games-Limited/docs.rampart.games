---
description: Quick Guide on steam updates
icon: turn-up
---

# DayZ modding help

{% include "../../.gitbook/includes/dayz.md" %}

### For Mod installations This Guide will teach you how to export a modlist.html to place with your server files for the mods autoloading and distribution.

\
Prepare Server for new mod installations.
-----------------------------------------

{% stepper %}
{% step %}
### Turn off your server

To avoid potential Corruption of files.
{% endstep %}

{% step %}
### Back Up files and download

* Mpmissions Folder

&#x20;\- The contents of this folder often gets wiped removing all data if not backed up, saving this and uploading again after steam update will save you alot of time resolving issues.
{% endstep %}

{% step %}
### Check for updates

* Check for updates on mods you have installed.

&#x20;  \- Update as Required, to avoid issues.
{% endstep %}
{% endstepper %}

## Getting Started with the new modlist

{% stepper %}
{% step %}
### Browse the steam workshop and subscribe to mods

* Click Subscribe on the mods you wish to use (the green +).

<figure><img src="../../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Launch Dayz via steam

* Once loaded the Dayz Launcher will appear Click mods
* Select More & "Export List of mods to file" Selecting All Mods or Only Loaded mods as you require.

<figure><img src="../../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Save File

name the file modlist.html
{% endstep %}

{% step %}
### Upload

Now upload the file to the root directory of the game server

<figure><img src="../../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Start Server

With modlist installed Start the server up and allow installations, this can be seen as pictured in the Console.

* Depending how many mods you want to load, this could take some time

&#x20;    \- It will move any Bikeys to allow the mods to work correctly for you.

<figure><img src="../../.gitbook/assets/image (2) (1).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Issues With mods

If you have issues with the installed mods, it is reccomended to install 1 mod at a time to find the issue, issues usually are due to outdated mod, Dependancies not installed, mods clashing with other mods.
{% endstep %}

{% step %}
### Enjoy


{% endstep %}
{% endstepper %}
