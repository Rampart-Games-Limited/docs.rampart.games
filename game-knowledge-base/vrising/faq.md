# Faq

<details>

<summary>How can i add myself as admin?</summary>

1\) Find the _adminlist.txt file and add your Steam id into this file._

* This can be done even with the server running, however the game checks every 5 mins for new inserts in this file, so be prepared to wait a short while.

Once you have waited for 5 mins (assuming you have not restarted server, ou will now have to follow the instructions below.

1\) Ingamne press Esc (Escape) Key on your keyboard

2\) Click Options to ensure "Console Enabled" is active

3\) use the \~ key to open console

4\) Type/paste "Adminauth" to Authorise your steam id as a admin.

* You should see a message appear as a message from \[System] "You now have Administrator privileges"

5\) For a list of admin commands Type/paste "list" to the console

</details>

<details>

<summary>Why isn’t my server showing up in the server list?</summary>

Common issues:

* Server still loading world data
* Wrong or blocked ports
* Filters in the server browser hiding your server
* Version mismatch after a patch
* Server set to **LAN mode**<br>

**Please contact Rampart support if none of these are your issue**

</details>

<details>

<summary>How do I change PvP or PvE settings?</summary>

Edit **ServerGameSettings.json**.\
You can modify:

* PvE / PvP / Full Loot PvP
* Damage modifiers
* Siege timers
* Castle raid settings
* Blood drain + death penalties
* Resource drop rates
* Sun damage
* Clan size

</details>

<details>

<summary>How do I wipe my V Rising server?</summary>

A wipe is done by deleting your world save folder:

```
VRisingServer/Saves/<SaveName>/
```

Make sure the server is **stopped** before wiping.

</details>

<details>

<summary>How do I install mods?</summary>

V Rising supports modding through community tools, not official Workshop.\
Steps generally include:

1. Install the mod loader used by the mod.
2. Place mod files in the required directory.
3. Restart server and ensure clients have matching mods.

(Compatibility varies depending on version and mod loader.)

</details>

<details>

<summary>Can I change clan size or castle limitations?</summary>

Yes — in **ServerGameSettings.json**:

* Clan size
* Number of castles per player
* Castle deterioration rate
* Siege damage settings
* PvP timers

These settings help customize your server’s gameplay style.

</details>
