# cs2_cfg
Counter Strike 2 personal configuration

## Download

1. Clone: `git clone https://github.com/MagicJoseph/cs2_cfg.git`
2. Download ZIP: [https://github.com/MagicJoseph/cs2_cfg/archive/refs/heads/main.zip](https://github.com/MagicJoseph/cs2_cfg/archive/refs/heads/main.zip)

## Installation
Place the configuration files in the Counter Strike 2 game directory given below:

1. All files from the `cfg` directory - `C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg`
2. cs2_video.txt, where `${steamID}` is steamID3 - `C:\Program Files (x86)\Steam\userdata\${steamID}\730\local\cfg`

The file cs2_video.txt was added to keep the game's private configuration in the repository. Keep in mind that the graphics settings I have used may not be proper in your case.

## Launch Options

`-freq 144 -novid -tickrate 128 -language english -d3d9ex +cl_forcepreload 1 +mat_queue_mode 2 -nojoy +exec autoexec.cfg`

## Files

```
|-- cs2_cfg
    |-- README.md
    |-- cs2_video.txt
    |-- cfg
        |-- audio_settings.cfg
        |-- autoexec.cfg
        |-- crosshair_default.cfg
        |-- crosshair_green.cfg
        |-- crosshair_line_up.cfg
        |-- crosshair_primary.cfg
        |-- crosshair_secondary.cfg
        |-- crosshair_tertiary.cfg
        |-- crosshair_white.cfg
        |-- practise.cfg
        |-- pt_help.cfg
        |-- userconfig.cfg
        |-- viewmodel_default.cfg
        |-- viewmodel_primary.cfg
```

## Key Binds
This table outlines a series of keybindings. The **KeyCode** column lists specific keys or mouse buttons, such as `ESCAPE`, `SPACE`, or `MOUSE1`. The **Action** column shows the in-game command each key or button triggers, like `cancelselect`, `+jump`, or `+attack`. The **Description** column provides a brief explanation of the command's function, for example, `+jump` is used to make the character jump, and `buymenu` opens the in-game purchase menu.

| KeyCode     | Action                            | Description                                               |
|-------------|-----------------------------------|-----------------------------------------------------------|
| ESCAPE      | `cancelselect`                    | Cancels the current selection.                            |
| `           | `toggleconsole`                   | Toggles the game console on and off.                      |
| TAB         | `+showscores`                     | Displays the score board.                                 |
| SPACE       | `+jump`                           | Makes the character jump.                                 |
| ,           | `buyammo1`                        | Buys primary weapon ammunition.                           |
| .           | `buyammo2`                        | Buys secondary weapon ammunition.                         |
| 0           | `slot10`                          | Selects item in slot 10.                                  |
| 1           | `slot1`                           | Selects item in slot 1.                                   |
| 2           | `slot2`                           | Selects item in slot 2.                                   |
| 3           | `slot3`                           | Selects item in slot 3.                                   |
| 4           | `slot4`                           | Selects item in slot 4.                                   |
| 5           | `slot5`                           | Selects item in slot 5.                                   |
| 6           | `slot12`                          | Selects item in slot 12.                                  |
| 7           | `slot7`                           | Selects item in slot 7.                                   |
| 8           | `slot8`                           | Selects item in slot 8.                                   |
| 9           | `slot9`                           | Selects item in slot 9.                                   |
| a           | `+left`                           | Moves character or view left.                             |
| b           | `buymenu`                         | Opens the buy menu.                                       |
| c           | `slot8`                           | Selects item in slot 8.                                   |
| d           | `+right`                          | Moves character or view right.                            |
| e           | `+use`                            | Activates the use function.                               |
| f           | `+lookatweapon`                   | Inspects the currently equipped weapon.                   |
| g           | `drop`                            | Drops the currently equipped item or weapon.              |
| i           | `show_loadout_toggle`             | Toggles the loadout display.                              |
| m           | `teammenu`                        | Opens the team selection menu.                            |
| q           | `+quickSwitch`                    | Quickly switches to the previous weapon.                  |
| r           | `+reload`                         | Reloads the currently equipped weapon.                    |
| s           | `+back`                           | Moves character backward.                                 |
| t           | `+crosshairLineup`                | Special function for crosshair alignment.                 |
| u           | `messagemode2`                    | Opens chat for team messages.                             |
| v           | `+voicerecord`                    | Starts voice recording or voice chat.                     |
| w           | `+forward`                        | Moves character forward.                                  |
| x           | `slot7`                           | Selects item in slot 7.                                   |
| y           | `messagemode`                     | Opens chat for all players.                               |
| z           | `+spray_menu`                     | Opens a menu for spray tags.                              |
| CTRL        | `+duck`                           | Makes the character crouch.                               |
| SHIFT       | `+sprint; radar_scale`            | Enables sprinting and adjusts radar scale.                |
| ALT         | `+jump; +throw`                   | Combines jump and throw actions.                          |
| F1          | `vote_yes; qb_ak47_m4a1`          | Votes yes and performs a quick buy of an AK-47/M4A1 set.  |
| F2          | `vote_no; qb_galilar_famas`       | Votes no and performs a quick buy of a Galil AR/FAMAS set.|
| F3          | `qb_mac10_mp9`                    | Performs a quick buy of a MAC-10/MP9 set.                 |
| F4          | `qb_deagle`                       | Performs a quick buy of a Desert Eagle set.               |
| F5          | `qb_tec9_cz75a`                   | Performs a quick buy of a Tec-9/CZ75-Auto set.            |
| F6          | `qb_awp`                          | Performs a quick buy of an AWP sniper rifle set.          |
| F7          | `qb_ssg08`                        | Performs a quick buy of an SSG 08 sniper rifle set.       |
| F8          | `exec crosshair_default.cfg`      | Executes the default crosshair configuration.             |
| F9          | `exec crosshair_primary.cfg`      | Executes the primary crosshair configuration.             |
| F10         | `exec crosshair_secondary.cfg`    | Executes the secondary crosshair configuration.           |
| F11         | `exec crosshair_tertiary.cfg`     | Executes the tertiary crosshair configuration.            |
| MWHEELDOWN  | `+jump`                           | Jump using mouse wheel down.                              |
| MWHEELUP    | `+duck`                           | Crouch using mouse wheel up.                              |
| MOUSE1      | `+attack`                         | Primary weapon attack or action.                          |
| MOUSE2      | `+attack2`                        | Secondary weapon attack or action.                        |
| MOUSE4      | `+lobThrow`                       | Executes a lobbed throw.                                  |
| MOUSE5      | `player_ping`                     | Pings a location or object for teammates to see.          |
| DEL         | `mute`                            | Mutes a selected player or sound source.                  |

## Aliases
The provided table lists a set of alias commands. It includes three columns: **Alias**, **Command**, and **Description**. Each row corresponds to a different alias, showing the shortcut, the complete command it represents, and a brief explanation of the command's function.


| Alias | Command              | Description                              |
|-------|----------------------|------------------------------------------|
| dc    | `disconnect`         | Disconnects from the current server.     |
| rt    | `retry`              | Reconnects to the current server.        |
| ae    | `exec autoexec.cfg`  | Executes the autoexec configuration file.|
| uc    | `exec userconfig.cfg`| Executes the user configuration file.    |
| pt    | `exec practice.cfg`  | Executes the practice configuration file.|


## Practice Configuration
This table outlines a configuration file for practicing grenade throws and other maneuvers. It includes bindings that help in setting up different training scenarios, managing bots for realistic simulations, and enabling various debug options to enhance learning and practice.

| Key  | Command               | Description                                                    |
|------|-----------------------|----------------------------------------------------------------|
| F1   | `pt_help`             | Displays a list of available keybinds.                         |
| F2   | `pt_give_nades`       | Provides all types of grenades for practice.                   |
| F3   | `pt_give_ak47`        | Equips the player with an AK-47 rifle.                         |
| F4   | `pt_give_m4a1`        | Equips the player with an M4A1 rifle.                          |
| F5   | `bot_add T`           | Adds a terrorist bot to the game for target practice.          |
| F6   | `bot_place`           | Places the added bot at the player's crosshair.                |
| F7   | `pt_bot_crouch`       | Commands the bot to crouch.                                    |
| F8   | `pt_bot_mimic`        | Makes the bot mimic the player’s actions.                      |
| F9   | `pt_wallhack`         | Toggles wallhack visibility for better visuals.                |
| F10  | `pt_impactmarker`     | Shows where projectiles impact for analysis.                   |
| h    | `pt_kill_projectile`  | Destroys a projectile in mid-air.                              |
| j    | `sv_rethrow_last_grenade` | Retrows the last grenade for repeated practice.          |
| v    | `noclip`              | Toggles no-clip mode, allowing movement through objects.       |

