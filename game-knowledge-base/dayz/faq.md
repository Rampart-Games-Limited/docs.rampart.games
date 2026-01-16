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

<summary>I Installed mods using the modding help guide but it crashes my server on startup</summary>

Mod Installation Failure?

* Check to see if the mod have and Requirements such as CF Tools.
* Check on the mods installation instructions, some mods require changes to be made to the xmls such as loot spawn and new ai, these will need new containers adding to the game.&#x20;

Players cannot join after mod install?

* Ensure you have the correct pbo on the server
* Ensure you have not removed the "dayz.bikey"
* Ensure a mod conflict doesn't exist
* Ensure all mods are updated
* Check to see if adjusting global settings has created this issue.

</details>

<details>

<summary>I cannot see my server on the server list</summary>

I do not see my server listed

* It could take 10-15 mins to list your game server on the master list
* The DayZ server list can sometimes have "well known issues", please try using [https://dayzsalauncher.com/](https://dayzsalauncher.com/) You may beable to find your server on this list.
* Check to ensure your server has the "online" status showing, your server may have a issue and may have not completed booting up.

</details>

<details>

<summary>How Can i set Restart Timer for the game</summary>

Setting Up the Ingame Built Restart Timer

*   Locate your messages.xml<br>

    ```
    mpmissions/dayzOffline.chernarusplus/db/messages.xml
    ```
*   Add the below message block to your file<br>

    ```
        <message>
            <deadline>240</deadline>
            <shutdown>1</shutdown>
            <text>#name will shutdown in #tmin minutes.</text>
        </message>
    ```

    \
    This should then restart your server every 240 mins and give your players a warning.\
    \
    Full file Below if you wish to just copy and replace everything in the file<br>

    ```
    <?xml version="1.0" encoding="UTF-8" standalone="yes"?>
    <messages>
        <message>
            <deadline>240</deadline>
            <shutdown>1</shutdown>
            <text>#name will shutdown in #tmin minutes.</text>
        </message>
    <!--
    See https://community.bistudio.com/wiki/DayZ:Server_Messages for more information

    Example messages:

    1) following message will be displayed to every player in countdown manner
        and shuts down server in 10 hours from its start

        <message>
            <deadline>600</deadline>
            <shutdown>1</shutdown>
            <text>#name will shutdown in #tmin minutes.</text>
        </message>


    2) following message will be displayed every 15 minutes to every player

        <message>
            <repeat>15</repeat>
            <text>You're playing on my server (#name). Thank you .)</text>
        </message>


    3) following message will be displayed every 50 minutes to every player
        and 10 minutes after player connect

        <message>
            <delay>10</delay>
            <repeat>50</repeat>
            <onconnect>1</onconnect>
            <text>Check our web page at www.dayz.com</text>
        </message>


    4) following message will be displayed once
        and 2 minutes after player connect

        <message>
            <delay>2</delay>
            <onconnect>1</onconnect>
            <text>Welcome to my server #name</text>
        </message>
        -->

    </messages>
    ```
* Restart your server for it to take effect.

</details>
