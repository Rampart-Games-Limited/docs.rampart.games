# Admin Commands

* **#Announce \<Message>** – Sends the announcement message to all currently connected players.

\


* **#DumpAllSquadsInfoList** – Copies all of the squad's information to your clipboard.

\


* **#Location \<Player>** – Displays a player's current location; if no player is specified, shows your own.

\


* **#ListAnimals** – Displays a list of all spawnable animals.

\


* **#ListItems \<String>** – Lists all assets matching the string; if none specified, lists all items.

\


* **#ListMutedPlayers** – Displays a list of all currently muted players.

\


* **#ListPlayers** – Displays a list of all connected players.

\


* **#ListSpawnedVehicles** – Displays all vehicles on the server and their locations.

\


* **#ListSquadMembers \<SquadID> \<True/False>** – Shows members of a squad; true copies it to clipboard.

\


* **#ListSquads** – Displays a list of all squads on the server.

\


* **#ListZombies** – Displays a list of all spawnable puppets.

\


* **#ShowFlagInfo \<True/False>** – Shows the flag’s location and information on the map.

\


* **#Vote SetWeather <0-1>** – Starts a weather vote; players vote with F2 (Yes) or F3 (No).

\


* **#Vote SetTimeOfDay <0-24>** – Starts a time-of-day vote; players vote with F2 (Yes) or F3 (No).

\


* **#Vote InitiateCargoDrop** – Starts a cargo drop vote; players vote with F2 (Yes) or F3 (No).

\


* **#CancelVote** – Cancels the currently ongoing vote.

\


* **#VisualizeBulletTrajectories \<True/False>** – Toggles bullet trajectory visualization for the command user.

\


* **#VisualizePlayerAiming \<True/False>** – Toggles player aim direction visualization for the command user.

\


### Environment Commands <a href="#id-2-environment-commands" id="id-2-environment-commands"></a>

\


* **#NightBrightness** – Toggles night brightness client-side; 1 = brighter night, 0 = darker night.

\


* **#SetTime <0–24>** – Sets in-game time of day to the specified hour.

\


* **#SetWeather <0–1>** – Sets weather intensity; 0 = sunny, 1 = full storm, values in between = mild conditions.

\


* **#ReloadCustomMapConfig** – Reloads custom map settings and size without restarting the server (wait 30 seconds after saving changes).

\


### Player Commands <a href="#id-2-player-commands" id="id-2-player-commands"></a>

\


* **#Ban \<SteamID64>** – Bans a player from the server until unbanned.

\


* **#Kick \<Player>** – Kicks the specified player from the game.

\


* **#Mute \<Player>** – Prevents the player from sending chat messages.

\


* **#ResetSquadInfo \<SquadID>** – Resets squad name and information.

\


* **#SetFakeName \<Name>** – Sets a fake character name displayed across various UI elements.

\


* **#ClearFakeName** – Clears the fake name set for your character.

\


* **#SetFamePoints \<Value> \<Player>** – Sets fame points for a player or yourself if no player is specified.

\


* **#SetFamePointsToAll \<Value>** – Sets fame points for all online and offline players.

\


* **#SetFamePointsToAllOnline \<Value>** – Sets fame points for all currently online players.

\


* **#SetGodMode \<True/False>** – Enables or disables god mode; requires "\\\[godmode\\]" suffix in AdminUsers.ini.

\


* **#Teleport \<X> \<Y> \<Z> \<Player>** – Teleports player (or yourself if unspecified) to specified coordinates.

\


* **#TeleportTo \<TargetPlayer> \<Player>** – Teleports a player (or yourself) to another player.

\


* **#TeleportToMe \<Player>** – Teleports a player to your location.

\


* **#TeleportToVehicle \<VehicleID> \<Player>** – Teleports a player (or yourself) to a vehicle by ID.

\


* **#Unban \<SteamID64>** – Unbans the specified player, allowing them to rejoin.

\


* **#UnMute \<Player>** – Unmutes the specified player, restoring chat access.

\


### Asset Commands <a href="#id-2-asset-commands" id="id-2-asset-commands"></a>

\


* **#DestroyAllVehicles Please** – Destroys all vehicles; must include "Please" or it will return "You have to ask nicely!".

\


* **#DestroyVehicle \<VehicleID>** – Destroys the vehicle with the specified ID.

\


* **#RenameVehicle \<ID or Alias> \<Alias>** – Renames a vehicle using its ID or alias; new alias must not be a number and is case-insensitive.

\


* **#SpawnAnimal \<ID> \<Amount>** – Spawns the specified number of animals with the given ID.

\


* **#SpawnItem \<ID> \<Count>** – Spawns the specified number of items in front of the invoking player.

\


* **#SpawnItem \<Weapon Magazine ID> \<Count> AmmoCount \<Fill Percentage>** – Spawns items with a set ammo percentage in front of the player.

\


* **#SpawnRandomAnimal** – Spawns a random animal in front of the invoking player.

\


* **#SpawnRandomZombie** – Spawns a random zombie (puppet) in front of the invoking player.

\


* **#SpawnVehicle \<ID>** – Spawns a vehicle in front of the invoking player.

\


* **#SpawnZombie \<ID> \<Count>** – Spawns a specified number of zombies of the given type.
