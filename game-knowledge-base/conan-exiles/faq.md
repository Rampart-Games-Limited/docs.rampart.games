---
icon: comment-question
---

# Faq

<details>

<summary>How do I fix performance issues ?</summary>

Try:

* Lowering player cap
* Reducing AI/creature counts
* Selecting a smaller or less intensive map
* Upgrading CPU/RAM resources
* Restarting the server regularly

</details>

<details>

<summary>Are backups available for my server?</summary>

All Servers at Rampart Come with a Backup System that you Control

* Quick and Efficient Backups
* Quick Backup Restoration!

</details>

<details>

<summary>How do i set my server to PVE-C ?</summary>

Locate the ServerSettings.ini file which should be located at the below location.

```
home/container/ConanSandbox/Saved/Config/WindowsServer/ServerSettings.ini
```

<figure><img src="../../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

you will need to change and set the two modifiers to the below\
\
set the below settings to: \
CombatModeModifier=1 \
&#x20;PVPEnabled=True

<figure><img src="../../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

If you would like to set days to allow for pvp time edit the below Variables\
PVPTimeMondayStart=0\
PVPTimeTuesdayStart=0\
PVPTimeWednesdayStart=0\
PVPTimeThursdayStart=0\
PVPTimeFridayStart=0\
PVPTimeSaturdayStart=0\
PVPTimeSundayStart=0\
PVPTimeMondayEnd=0\
PVPTimeTuesdayEnd=0\
PVPTimeWednesdayEnd=0\
PVPTimeThursdayEnd=0\
PVPTimeFridayEnd=0\
PVPTimeSaturdayEnd=0\
PVPTimeSundayEnd=0\
PVPEnabledMonday=False\
PVPEnabledTuesday=False\
PVPEnabledWednesday=False\
PVPEnabledThursday=False\
PVPEnabledFriday=False\
PVPEnabledSaturday=False\
PVPEnabledSunday=False\
PVPBuildingDamageTimeMondayStart=0\
PVPBuildingDamageTimeTuesdayStart=0\
PVPBuildingDamageTimeWednesdayStart=0\
PVPBuildingDamageTimeThursdayStart=0\
PVPBuildingDamageTimeFridayStart=0\
PVPBuildingDamageTimeSaturdayStart=0\
PVPBuildingDamageTimeSundayStart=0\
PVPBuildingDamageTimeMondayEnd=0\
PVPBuildingDamageTimeTuesdayEnd=0\
PVPBuildingDamageTimeWednesdayEnd=0\
PVPBuildingDamageTimeThursdayEnd=0\
PVPBuildingDamageTimeFridayEnd=0\
PVPBuildingDamageTimeSaturdayEnd=0\
PVPBuildingDamageTimeSundayEnd=0\
\
to enable pvp to be set for specific days please set the variables to true. Example below

```
PVPEnabledSunday=true
```

you can also allow damage to buildings by setting the below\


```
PVPBuildingDamageTimeSundayStart=12
PVPBuildingDamageTimeSundayEnd=13
```

This will allow damage for 1 hour to all buildings \
Which in effect would allow you to set the below\


```
PVPTimeSundayStart=12
PVPTimeSundayEnd=13
```

This will now allow for Full pvp on your server between 1200 and 1300 Hours local time of the host machine.\
which includes

* PVP
* Damage to buildings

Therefore this will allow for raiding a enemy base and killing the defenders.



Ensure after your edits, you save the file and restart the server

</details>
