# Faq

<details>

<summary>Where do I find the SCUM server configuration files?</summary>

*   Server configs are usually located in:

    ```
    SCUM/Saved/Config/WindowsServer/
    ```


* Key files include:
  * **ServerSettings.ini** – basic server settings
  * **Gameplay.ini** – loot, metabolism, zombies, survival settings
  * **EconomyOverrides.json** – economy/shop settings

</details>

<details>

<summary>How do I change the server name, password, and max players?</summary>

This can be done in the "StartUp" Area in the left menu of the Game panel

</details>

<details>

<summary>How do I get admin access?</summary>

Add your SteamID64 to the **Admins.txt** file (location varies by host), or use the hosting panel.

Admin commands are used in chat with a hashtag, such as:

```
#listplayers
#kick <ID>
#teleport <player> <location>
```

</details>

<details>

<summary>How do I change loot, weather, zombies, metabolism, or survival settings?</summary>

Adjust these in **Gameplay.ini**, which controls:

* Zombie counts
* Loot respawn rates
* Vehicle spawns
* Weather frequency
* Base building settings
* Stamina, metabolism, calorie, and hydration rates

These settings allow you to make SCUM harder or easier depending on your community style.

</details>

<details>

<summary>How do i wipe my server?</summary>

A server wipe usually means deleting:

* **Saved/SaveFiles/** (world & character data)
* Economy files (optional)

You can perform:

* **Character wipe only**
* **Base wipe**
* **Full wipe** (world + characters + bases)

Always stop the server first.

</details>

<details>

<summary>How do i add server mods?</summary>

If you are using Steam Workshop or direct mod support:

1. Download the mod files.
2. Upload them to the appropriate server folder.
3. Add the mod IDs or files to the server startup parameters (if required).
4. Restart your server.

Note: Some mod types require client-side installation too.

</details>

<details>

<summary>Why is my SCUM server performing poorly?</summary>

Possible reasons:

* Too many AI (zombies, puppets, animals)
* Excessively high loot settings
* High player count or vehicles
* Heavy mods
* Large bases and structures

Try lowering intensive settings in **Gameplay.ini** or upgrading your hosting resources.\
Ram is easily upgradable and is instant upon payment.

</details>
