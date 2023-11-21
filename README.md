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
        |-- userconfig.cfg
        |-- viewmodel_default.cfg
        |-- viewmodel_primary.cfg
```

### Key Binds

| KeyCode     | Action                            |
|-------------|-----------------------------------|
| ESCAPE      | `cancelselect`                    |
| `           | `toggleconsole`                   |
| TAB         | `+showscores`                     |
| SPACE       | `+jump`                           |
| ,           | `buyammo1`                        |
| .           | `buyammo2`                        |
| 0           | `slot10`                          |
| 1           | `slot1`                           |
| 2           | `slot2`                           |
| 3           | `slot3`                           |
| 4           | `slot4`                           |
| 5           | `slot5`                           |
| 6           | `slot6`                           |
| 7           | `slot7`                           |
| 8           | `slot8`                           |
| 9           | `slot9`                           |
| a           | `+left`                           |
| b           | `buymenu`                         |
| c           | `slot10`                          |
| d           | `+right`                          |
| e           | `+use`                            |
| f           | `+lookatweapon`                   |
| g           | `drop`                            |
| i           | `show_loadout_toggle`             |
| m           | `teammenu`                        |
| q           | `+quickSwitch`                    |
| r           | `+reload`                         |
| s           | `+back`                           |
| t           | `+crosshairLineup`                |
| u           | `messagemode2`                    |
| v           | `+voicerecord`                    |
| w           | `+forward`                        |
| x           | `slot7`                           |
| y           | `messagemode`                     |
| z           | `+spray_menu`                     |
| CTRL        | `+duck`                           |
| SHIFT       | `+sprint; radar_scale`            |
| ALT         | `+jump; +throw`                   |
| F1          | `vote_yes; qb_ak47_m4a1`          |
| F2          | `vote_no; qb_galilar_famas`       |
| F3          | `qb_mac10_mp9`                    |
| F4          | `qb_deagle`                       |
| F5          | `qb_tec9_cz75a`                   |
| F6          | `qb_awp`                          |
| F7          | `qb_ssg08`                        |
| F8          | `exec crosshair_default.cfg`      |
| F9          | `exec crosshair_primary.cfg`      |
| F10         | `exec crosshair_secondary.cfg`    |
| F11         | `exec crosshair_tertiary.cfg`     |
| MWHEELDOWN  | `+jump`                           |
| MWHEELUP    | `+duck`                           |
| MOUSE1      | `+attack`                         |
| MOUSE2      | `+attack2`                        |
| MOUSE4      | `+lobThrow`                       |
| MOUSE5      | `player_ping`                     |
| DEL         | `mute`                            |
