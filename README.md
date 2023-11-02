# cs2_cfg
Counter Strike 2 personal configuration

## Download

Clone: `git clone https://github.com/MagicJoseph/cs2_cfg.git`

Download ZIP: [https://github.com/MagicJoseph/cs2_cfg/archive/master.zip](https://github.com/MagicJoseph/cs2_cfg/archive/master.zip)

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
        |-- userconfig.cfg
        |-- viewmodel_default.cfg
        |-- viewmodel_primary.cfg
```
