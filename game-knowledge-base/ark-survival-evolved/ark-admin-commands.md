# Ark Admin Commands

{% include "../../.gitbook/includes/arkbanner.md" %}

| Command                        | Function                                                                                                       |
| ------------------------------ | -------------------------------------------------------------------------------------------------------------- |
| enablecheats                   | Enable server administrator commands for the current player (only needed for multiplayer).                     |
| ce                             | Starts and stops weather of type specified.                                                                    |
| gamecommand                    | Runs a game-mode specific command.                                                                             |
| gfi                            | Adds the specified item or blueprint to the player's inventory.                                                |
| playersonly                    | Toggle on/off all creature movement and crafting. Player movement unaffected.                                  |
| printcolors                    | Prints all Color IDs in the console for reference.                                                             |
| startnearesthorde              | Spawns an Orbital Supply Drop or Element Node at the nearest location to you.                                  |
| listactivehordeevents          | Lists all active Orbital Supply Drops and Element Nodes.                                                       |
| scriptcommand                  | Runs a game-mode specific command/script.                                                                      |
| slomo                          | Sets the game speed multiplier (default 1).                                                                    |
| enablespectator                | Set game mode to spectator.                                                                                    |
| requestspectator               | Requests spectator mode on servers where there is a spectator password.                                        |
| setshowallplayers              | Show/hide player names in spectator mode.                                                                      |
| disablespectator               | Exits spectator mode.                                                                                          |
| stopspectating                 | Leaves spectator mode which was enabled with "enablespectator".                                                |
| toggledamagenumbers            | Toggles on/off floating damage numbers.                                                                        |
| hatchegg                       | Sets incubating progress of target egg to 0%.                                                                  |
| allowplayertojoinnocheck       | Adds specified player to the server whitelist.                                                                 |
| banplayer                      | Bans the specified player.                                                                                     |
| broadcast                      | Broadcast a message to all players on the server.                                                              |
| tribemessage                   | Adds a message to the specified tribe's Tribelog.                                                              |
| disallowplayertojoinnocheck    | Removes specified player from the server whitelist.                                                            |
| doexit                         | Shuts down the server.                                                                                         |
| getchat                        | Returns the latest chat buffer.                                                                                |
| getgamelog                     | Print 100 entries at a time. Also outputs dated file in "\Logs".                                               |
| gettribeidplayerlist           | Prints a list of every player of a specified tribe.                                                            |
| tribestructureaudit            | Prints types and counts of specified tribe's structures.                                                       |
| Advertisement                  |                                                                                                                |
| tribedinoaudit                 | Prints types and counts of specified tribe's dinos.                                                            |
| serverchat                     | Sends a chat message to all currently connected players.                                                       |
| serverchatto                   | Sends a direct chat message to the specified player.                                                           |
| serverchattoplayer             | Sends a direct chat message to the specified player.                                                           |
| saveworld                      | Forces the server to save.                                                                                     |
| setglobalpause                 | Pauses/Unpauses the game.                                                                                      |
| settimeofday                   | Sets the time of day.                                                                                          |
| showmessageoftheday            | Displays the message of the day.                                                                               |
| unbanplayer                    | Unbans the specified player.                                                                                   |
| setcheatplayer                 | Enable cheat commands that affect the current player.                                                          |
| clearplayerinventory           | Clears inventory of the specified player.                                                                      |
| getallstate                    | Prints all entities of the specified type to console.                                                          |
| giveexptotarget                | Gives specified amount of XP to target.                                                                        |
| giveinfinitestatstotarget      | Gives infinite stats to target.                                                                                |
| kickplayer                     | Kicks the specified player from the server.                                                                    |
| kill                           | Instantly kills the target structure or dino.                                                                  |
| killaoe                        | Instantly kills all targets of specified type within specified radius.                                         |
| killplayer                     | Kills the specified player.                                                                                    |
| renameplayer                   | Renames the specified player.                                                                                  |
| renametribe                    | Renames the specified tribe.                                                                                   |
| takealldino                    | Changes ownership of all dinos from target tribe to player's tribe.                                            |
| takeallstructure               | Changes ownership of all structures from target tribe to player's tribe.                                       |
| levelup                        | Levels up target stat for your character.                                                                      |
| levelupaoe                     | Levels up target stat for all targets within radius.                                                           |
| leveluptarget                  | Levels up target stat for target.                                                                              |
| teleport                       | Moves player character forward in the direction they are facing.                                               |
| teleportplayeridtome           | Teleports the specified player to the current player.                                                          |
| teleportplayernametome         | Teleports the specified player to the current player.                                                          |
| Advertisement                  |                                                                                                                |
| teleporttoplayer               | Teleports current player to the specified player.                                                              |
| teleporttoplayername           | Teleports current player to the specified player.                                                              |
| teleporttoactorlocation        | Teleports current player to the specified target.                                                              |
| tp                             | Teleport to the specified defined location.                                                                    |
| tpcoords                       | Teleports to the specified coordinates.                                                                        |
| spi                            | Teleports to the specified coordinates. Allows you to also set yaw and pitch.                                  |
| setplayerpos                   | Teleports player to specified coordinates.                                                                     |
| movetargetto                   | Teleports target to specified coordinates.                                                                     |
| teleporttoactivehorde          | Teleports player to the specified horde event.                                                                 |
| destroyall                     | Destroys all creatures of specified type.                                                                      |
| destroyallenemies              | Destroys all non-player creatures.                                                                             |
| destroymytarget                | Destroys target creature.                                                                                      |
| destroystructures              | Destroys all structures.                                                                                       |
| destroytribedinos              | Destroys all dinos owned by target tribe.                                                                      |
| destroytribeid                 | Destroys specified tribe.                                                                                      |
| destroytribeiddinos            | Destroys all dinos owned by specified tribe.                                                                   |
| destroytribeidplayers          | Destroys all players in specified tribe.                                                                       |
| destroytribeidstructures       | Destroys all structures in specified tribe.                                                                    |
| destroytribeplayers            | Destroys all players in target tribe.                                                                          |
| destroytribestructures         | Destroys all structures in target tribe.                                                                       |
| destroytribestructureslessthan | Destroys all structures in specified tribe that have less than the specified connections (snapped structures). |
| destroywilddinos               | Destroys all untamed dinos.                                                                                    |
| forceplayertojointargettribe   | Forces specified player to join target tribe.                                                                  |
| forceplayertojointribe         | Forces specified player to join specified tribe.                                                               |
| forcejointribe                 | Lets you join target tribe.                                                                                    |
| forcetribes                    | Creates a new tribe and forces specified players to join it.                                                   |
| giveallstructure               | Gives current player ownership of target structure and all connected structures.                               |
| maketribeadmin                 | Makes you admin of your current tribe.                                                                         |
| Advertisement                  |                                                                                                                |
| maketribefounder               | Makes you founder of your current tribe.                                                                       |
| removetribeadmin               | Removes your admin status for current tribe.                                                                   |
| taketribe                      | Gives you all of the specified tribe's dinos and structures.                                                   |
| givecreativemode               | Sets game mode to creative.                                                                                    |
| givecreativemodetotarget       | Sets game mode of target player to creative.                                                                   |
| givecreativemodetoplayer       | Sets game mode of specified player to creative.                                                                |
| addexperience                  | Adds specified amount of XP.                                                                                   |
| unlockengram                   | Unlocks Tek Engram.                                                                                            |
| hideriders                     | Toggle on/off rider invisibility.                                                                              |
| changesize                     | Changes player size (default 1).                                                                               |
| cleartutorials                 | Resets all tutorials.                                                                                          |
| enemyinvisible                 | Toggle on/off hostility. When enabled, all creatures will ignore you.                                          |
| execsetsleeping                | Puts current player to sleep or wakes them up.                                                                 |
| fly                            | Activates fly mode.                                                                                            |
| ghost                          | Activates ghost mode, allowing you to pass through objects/terrain.                                            |
| givecolors                     | Gives the specified quantity of each dye.                                                                      |
| giveengrams                    | Unlocks all crafting recipes for player.                                                                       |
| giveengramstekonly             | Gives all tek engrams to player.                                                                               |
| givetekengramsto               | Gives all tek engrams to specified player.                                                                     |
| giveexptoplayer                | Gives specified player the specified amount of XP.                                                             |
| giveitem                       | Adds the specified item to the player's inventory.                                                             |
| giveitemnum                    | Adds the specified item to the player's inventory.                                                             |
| giveitemtoplayer               | Adds the specified item to the specified player's inventory.                                                   |
| giveitemnumtoplayer            | Adds the specified item to the specified player's inventory.                                                   |
| giveresources                  | Adds 50 of each resource to player's inventory.                                                                |
| giveslotitem                   | Adds specified item to specified item slot.                                                                    |
| giveslotitemnum                | Adds specified item to specified item slot.                                                                    |
| givetome                       | Changes ownership of target dino or structure to current player.                                               |
| Advertisement                  |                                                                                                                |
| gmbuff                         | Executes the "god", "infinitestats", and "enemyinvisible" commands, and provides XP.                           |
| envqa                          | Executes the "gmbuff", "givearmorset tek 0", "stat fps", and "stat unit" commands.                             |
| god                            | Toggles invulnerability.                                                                                       |
| hidetutorial                   | Hides specified tutorial.                                                                                      |
| hurtme                         | Deals specified amount of damage to player.                                                                    |
| infinitestats                  | Sets all stats to maximum until command is repeated.                                                           |
| leavemealone                   | Executes the "god", "infinitestats", and "enemyinvisible" commands.                                            |
| ontoggleingamemenu             | Enables/disables opening of in-game menu when you hit ESC.                                                     |
| openmap                        | Loads the specified map.                                                                                       |
| playercommand                  | Gives the player the specified ascension effect.                                                               |
| setadminicon                   | Shows/hides your admin icon.                                                                                   |
| setfacialhairpercent           | Sets length of facial hair.                                                                                    |
| setfacialhairstyle             | Sets style of facial hair.                                                                                     |
| setheadhairpercent             | Sets length of head hair.                                                                                      |
| setheadhairstyle               | Sets style of head hair.                                                                                       |
| setgodmode                     | Enables/disables god mode.                                                                                     |
| settargetplayerbodyval         | Sets index of specified body region.                                                                           |
| settargetplayercolorval        | Sets color of specified body region.                                                                           |
| showingamemenu                 | Displays the in-game menu.                                                                                     |
| showtutorial                   | Displays the specified tutorial.                                                                               |
| suicide                        | Kill yourself (won't work with God mode enabled).                                                              |
| toggleinfiniteammo             | Toggles on/off infinite ammo.                                                                                  |
| walk                           | Deactivates fly mode.                                                                                          |
| togglegun                      | Disables/enables display of character's equipped item or hands.                                                |
| refillstats                    | Sets all stats to maximum (one-off, unlike infinitestats).                                                     |
| givearmorset                   | Gives you a full armor set of the specified tier and quality.                                                  |
| giveweaponset                  | Gives you a full weapon set of the specified tier and quality.                                                 |
| Advertisement                  |                                                                                                                |
| giveitemset                    | Gives you a full item set of the specified tier.                                                               |
| clearmybuffs                   | Clears all currently active buffs from player.                                                                 |
| setmytargetsleeping            | Knocks out target dino or player.                                                                              |
| maxascend                      | Unlocks all ascensions for specified player.                                                                   |
| defeatboss                     | Unlocks specified boss for specified player.                                                                   |
| defeatallbosses                | Unlocks all bosses for specified player.                                                                       |
| giveallexplorernotes           | Unlocks all explorer notes for player.                                                                         |
| giveexplorernote               | Unkocks specified explorer note for player.                                                                    |
| addhexagons                    | Adds specified number of hexagons.                                                                             |
| destroyall                     | Destroys all of a specified type of creature.                                                                  |
| destroyallenemies              | Destroys all non-player creatures.                                                                             |
| dotame                         | Tames the target creature, if possible.                                                                        |
| dumpdinostats                  | Dumps the stats for the target dino into the console.                                                          |
| forcetame                      | Tames the target dino.                                                                                         |
| forcetameaoe                   | Tames all dinos within specified radius (default 2000).                                                        |
| raincritters                   | Spawns mix of sheep and dodos above player.                                                                    |
| raindinos                      | Spawns mix of trikes and paranaurs above player.                                                               |
| raindanger                     | Spawns mix of rexes and allos above player.                                                                    |
| sdf                            | Spawn creature of specified type with random level.                                                            |
| setbabyage                     | Sets age of target baby dino.                                                                                  |
| setimprintquality              | Sets imprint quality of target dino.                                                                           |
| setimprintedplayer             | Changes imprinted player of target dino to specified player.                                                   |
| transferimprints               | Transfers all dinos imprinted on old playerid to new playerid.                                                 |
| settargetdinocolor             | Sets the target dino to specified colors.                                                                      |
| spawnactor                     | Spawns the specified entity at a random level.                                                                 |
| spawnactorspread               | Spawns the specified number of entities in the specified area.                                                 |
| spawndino                      | Spawns the specified dino at the specified level.                                                              |
| summon                         | Spawns the specified entity. Can be used to spawn beacons.                                                     |
| summontamed                    | Spawn a force-tamed creature of the specified type.                                                            |
| Advertisement                  |                                                                                                                |
| gmsummon                       | Spawns creature of specified type and tames it (but still requires saddle).                                    |
| givedinoset                    | Spawns a set of dinos in specified tier, fully set up with stats and saddles.                                  |
| spawnsetupdino                 | Spawns a dino set up to specifications.                                                                        |
| forcepoop                      | Forces target dino to poop.                                                                                    |
| clearcryosickness              | Removes cryo-sickness status from target.                                                                      |
| dino reset                     | Resets all blink cooldowns for target dino.                                                                    |
| dino infiniteblink             | Don't use blink cooldown slots, just always allow blinking for target dino.                                    |
| dinoset cooldowns              | Set number of blink cooldown slots for target dino.                                                            |
| dino donthideriderduringblink  | Prevents enforcer from touching rider visibility during blink for target dino.                                 |
| dinoset blink                  | Sets the blink vfx (forwards) to the specified percentage for target dino.                                     |
| dinoset blinkback              | Sets the blink vfx (forwards) to the specified percentage for target dino.                                     |
| dino inflate                   | Sets current inflation to maximum for target dino.                                                             |
| dinoset inflate                | Increases/decreases inflation of target dino by specified amount.                                              |
| dino infinitegas               | Constantly refills inflation for target dino. Keeps at maximum until command is repeated.                      |
| dino reset                     | Resets Mek fuel to maximum and heat level to zero for target dino.                                             |
| dino infinitefuel              | Keeps fuel at 100% for target dino.                                                                            |
| dinoset fuel                   | Adds/subtracts specified amount of fuel for target dino.                                                       |
| dino noheat                    | Keeps heat at 0% for target dino.                                                                              |
| dino toggleupkeep              | Disables/enables Mek upkeep for target dino.                                                                   |
| dinoset upkeepinterval         | Sets the Mek's upkeep interval in seconds for target dino.                                                     |
| dino replayintro               | Makes the MegaMek invisible, then replays the intro effect VFX.                                                |
| dinoset blink                  | Sets the blink/intro effect to specified level for target dino.                                                |
| dinoset eattime                | Sets time in seconds between sitting down to digest for target dino.                                           |
| dino destroyrightnode          | Dismembers right arm and destroys node for target dino.                                                        |
| Advertisement                  |                                                                                                                |
| dino destroyleftnode           | Dismembers left arm and destroys node for target dino.                                                         |
| dino destroycenternode         | Destroys center node for target dino.                                                                          |
| copycoordstoclipboard          | Copies current coordinates and rotation to clipboard (x y z yaw pitch).                                        |
| debugstructures                | Toggles debug info display when looking at structures.                                                         |
| stat                           | Enables on-screen debug display.                                                                               |
| showdebug                      | Enables on-screen debug display.                                                                               |
| setgraphicsquality             | Sets client graphics quality.                                                                                  |
| autocycle                      | Provides unlimited health for specified duration for player.                                                   |
| dorestartlevel                 | Restart the map.                                                                                               |
| getplayeridforsteamid          | Returns playerid for player with specified steamid.                                                            |
| getsteamidforplayerid          | Returns steamid for player with specified playerid.                                                            |
| teleporttoactorlocation        | Teleports you to the location of the specified actor.                                                          |
| addequipmentdurability         | Adds durability/water/energy to hotbar and equipped items.                                                     |
| dcmset                         | Sets a property on the Day Cycle Manager.                                                                      |
| debugallowvrmissionteleport    | Teleport to the final boss of Genesis: Part 1.                                                                 |
| destroyfoliage                 | Destroys all foliage and auto-harvests all resource nodes in specified radius.                                 |
| destroywilddinoclasses         | Destroys all wild dinos of the specified type.                                                                 |
| dino titanmode                 | Multiplies inflation x10.                                                                                      |
| findmutagendrops               | Console displays locations of nearby Mutagen Bulbs.                                                            |
| forcegivebuff                  | Forces a status effect on your character or dino mount.                                                        |
| forcemutagenspawn              | Forces a Mutagen Bulb to spawn nearby.                                                                         |
| forceupdatedynamicconfig       | Forces an update of the dynamic config.                                                                        |
| getegg                         | Spawns fertilised egg from targeted dino.                                                                      |
| infiniteweight                 | Removes weight restrictions from player inventory.                                                             |
| listmybuffs                    | Lists all buff IDs in the console.                                                                             |
| open                           | Join specified server.                                                                                         |
| previewmode                    | Changes appearance of game graphics.                                                                           |
| r.shadowquality                | Sets quality of shadow appearance.                                                                             |
| removeallworldbuffs            | Removes all map buffs (only in Genesis: Part 2).                                                               |
| Advertisement                  |                                                                                                                |
| setday                         | Sets the current day number.                                                                                   |
| setdifficultyvalue             | Sets the max level for wild dino spawns.                                                                       |
| setstatontarget                | Sets the value of the specified stat.                                                                          |
| spawnexactdino                 | Spawns a dino with the specified characteristics. (Warning: can cause game to crash!)                          |
