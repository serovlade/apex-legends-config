# Apex Legends Config

Apex Legends configuration files

## Origin

### Launch Options

```
+preload +exec autoexec.cfg +fps_max 225 +cl_showfps 4 +cl_ragdoll_collide 0 -refresh 240 -freq 240 -high -dev -fullscreen
```

### Game Settings

* autoexec.cfg - `C:\Program Files (x86)\Origin Games\Apex\cfg\autoexec.cfg`
* superglide1.cfg - `C:\Program Files (x86)\Origin Games\Apex\cfg\superglide1.cfg`
* superglide2.cfg - `C:\Program Files (x86)\Origin Games\Apex\cfg\superglide2.cfg`
* superglide3.cfg - `C:\Program Files (x86)\Origin Games\Apex\cfg\superglide3.cfg`

### Player Settings

* settings.cfg - `C:\Users\{username}\Saved Games\Respawn\Apex\local\settings.cfg`
* profile.cfg - `C:\Users\{username}\Saved Games\Respawn\Apex\profile\profile.cfg`

## r5reloaded

* startup_default.cfg `C:\Program Files\r5reloaded\platform\cfg\startup_default.cfg`

## How to Fix Footstep Audio

1. Right click taskbar sound icon
2. Open Sound Settings
3. Sound Control Panel
4. Choose your audio device (Usually "Speakers")
5. Properties -> Advanced
6. Under Default Format, select 16 bit 44100hz
7. Right click taskbar sound icon again
8. Spatial Sound
9. Select either Dolby Atmos or DTS HeadphoneX (you'll have to pay for these)
10. Edit `settings.cfg`
11. Change `sound_num_speakers "2"` to `sound_num_speakers "8"`
12. Use the `Audio` portion of the `autoexec.cfg` in this repository