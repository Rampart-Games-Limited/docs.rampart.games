---
description: Quick Guide on Dayz modding
icon: turn-up
---

# Dayz Admin Commands

{% include "../../.gitbook/includes/dayz.md" %}

#### DayZ Player Commands

| Command                          | Description                                             | Example             |
| -------------------------------- | ------------------------------------------------------- | ------------------- |
| #vote kick (name, ID or Player#) | Players can vote to kick another player off the server. | #vote kick nickName |
| #userlist                        | Provides a list of all players on the server.           | #userlist           |

#### DayZ Admin Commands

| Command                          | Description                                                                                                                                                                                                                             | Example                               |
| -------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------- |
| #login \<password>               | Used to login as a DayZ admin.                                                                                                                                                                                                          | #login adminPW                        |
| #logout                          | Logs out of admin access on the server.                                                                                                                                                                                                 | #logout                               |
| #shutdown                        | Usable to instantly turn off the server.                                                                                                                                                                                                | #shutdown                             |
| #init                            | Reloads your server configuration.                                                                                                                                                                                                      | #init                                 |
| #exec ban \<name, ID or Player#> | Executes a player ban of the name, ID, or player# that you provide.                                                                                                                                                                     | #exec ban nickName                    |
| #kick \<name, ID or Player#>     | Kicks the specified player off of your server.                                                                                                                                                                                          | #kick nickName                        |
| #monitor \<Interval in Seconds>  | Displays information about the performance on the server.                                                                                                                                                                               | #monitor 5                            |
| #debug \<Interval in Seconds>    | Sets a debug interval for your server. The default interval is 10.                                                                                                                                                                      | #debug 30                             |
| #debug off                       | Deactivates the debug.                                                                                                                                                                                                                  | #debug off                            |
| #debug \<Option> \<Parameter>    | Disables automatic game/server backups.                                                                                                                                                                                                 | #debug checkFile expansion\Dta\ui.pbo |
| #debug \<Option>                 | <p>The usable commands are:<br>Console (send to submitter what’s on server console, works as DebugAnswer for all writes into the console),<br>von (outputs into logFile defined in server.cfg as e.g. logFile=server_console.log”;)</p> | #debug von                            |

#### Admin Commands for BattlEye

| Command           | Description                        |
| ----------------- | ---------------------------------- |
| #beclient players | Lists the BE GUIDs of the players. |
| #beclient guid    | Shows your own BE GUID.            |

<br>
