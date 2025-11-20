# Faq

{% include "../../.gitbook/includes/minecraft.md" %}

<details>

<summary>How can i set autohealing?</summary>

find the _server.properties_ file called “auto-healing=”. \
To enable healing please ensure the field is set to true.

</details>

<details>

<summary>How do I become an admin (OP) on my server?</summary>

In the server console or terminal, run:

```
op <playername>
```

You can also edit `ops.json` manually.\


</details>

<details>

<summary>Why can’t my friends join my server?</summary>

Common reasons include:

* Incorrect **IP address given to them**
* Server is set to **offline-local** only
* Version mismatch

Please Contact Rampart Support so we can help you find the issue if it exists.

</details>

<details>

<summary>How do I install plugins? (Spigot/Paper)</summary>

* Download plugins in `.jar` format.
* Place them into the `/plugins` folder.
* Restart the server.\
  Only Spigot/Paper/Purpur servers support plugins—**Vanilla does not.**

</details>

<details>

<summary>How do I add mods? (Forge/Fabric)</summary>

* Install the correct version of **Forge** or **Fabric** on both the server and client.
* Place mod files in the `/mods` folder.
* Restart the server.\
  All players must have the same mods installed.

</details>

<details>

<summary>How do I change server settings?</summary>

Edit the **server.properties** file.\
Common options include:

* Difficulty
* Whitelist
* Max players
* MOTD
* View distance
* Game mode

Restart required after changes.

</details>

<details>

<summary>How do I whitelist players?</summary>

Enable the whitelist in `server.properties`:

```
white-list=true
```

Add players via console:

```
whitelist add <playername>
```

</details>

<details>

<summary>Can I upload my own world?</summary>

Yes. Replace the `/world` folder (and other dimension folders) with your own.\
Make sure the world matches the server version.

</details>

<details>

<summary>Can Bedrock and Java players join together?</summary>

Not by default.\
However, you _can_ with:

* **GeyserMC** (Bedrock → Java compatibility)
* **Floodgate** (optional add-on for Bedrock authentication)\
  Paper/Spigot/Purpur servers support these best.

</details>
