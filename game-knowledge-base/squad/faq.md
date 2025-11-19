# Faq

<details>

<summary>How can i get started with modding?</summary>

The [Squad SDK](https://squad.fandom.com/wiki/Squad_SDK) is the official Squad software development kit. It is recommended to get yourself familiarised with it to start modding your game server.

\
Below is a couple of useful links to help you get started\
\
[Squad Wiki](https://squad.fandom.com/wiki/Squad_SDK) \
[Squad SDK](https://squad.fandom.com/wiki/Squad_SDK)\


</details>

<details>

<summary>How do I become an admin on my Squad server?</summary>

Add your SteamID64 to **Admins.cfg** with the appropriate permission level:

```
Admin=<SteamID64>:<Level>
```

Example:

```
Admin=76561198000000000:Owner
```

Roles include: Owner, Admin, Moderator, and more.

</details>

<details>

<summary>How many players can my Squad server host?</summary>

Full official servers typically run **100–120 players** depending on performance.\
Performance depends on CPU speed—Rampart.Games uses optimized hardware for high-player servers.

</details>

<details>

<summary>Can I upload a custom server logo or banner?</summary>

Yes — in **Server.cfg**:

```
ServerBanner="URL_to_image"
```

Image must be online (direct link) and in a supported format like PNG or JPG.

</details>
