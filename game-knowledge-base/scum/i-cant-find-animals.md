---
description: Quick Guide on steam updates
icon: turn-up
---

# I can't Find Animals

{% include "../../.gitbook/includes/dayz.md" %}

### To Modify the amount of Animals Please follow the following steps

\
Prepare Server for new mod installations.
-----------------------------------------

{% stepper %}
{% step %}
### Turn off your server

To avoid potential Corruption of files.
{% endstep %}

{% step %}
### Find the config file

Find the ServerSettings.ini file which is located at:

```
/home/container/SCUM/Saved/Config/WindowsServer/ServerSettings.ini
```

<figure><img src="../../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Locate Line&#x20;

Locate the line with&#x20;

```
scum.MaxAllowedAnimals=-1
```

> ⚠️ Hint\
> \
> -1 in most programing logic is intended as a Default Variable (The game devs default number)

\
Replace with what you want for the purpose of this tutorial we will use 100.<br>

```
scum.MaxAllowedAnimals=100
```

This will now Spawn 100 Animals in the world.
{% endstep %}

{% step %}
### Save the File

Save the file by clicking Save content (bottom right)
{% endstep %}

{% step %}
### Start Server

Now Start the server and see if you have more Animals Available.\
Enjoy!
{% endstep %}
{% endstepper %}
