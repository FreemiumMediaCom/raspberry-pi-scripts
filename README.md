# raspberry-pi-scripts
Utilities and scripts for the Raspberry Pi

## script 'disable-screensaver.sh'
- Adds the following lines to the Autostart file located at: 
  - ~/.config/lxsession/LXDE-pi/autostart

```
@xset s off
@xset -dpms
@xset s noblank
@unclutter
```
