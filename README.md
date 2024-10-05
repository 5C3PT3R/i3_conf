This repo has the config files to customize your i3

the config files should be replaced in paths as follows

**config = ./.config/i3/config**
**config2 = ./.config/i3statusbar/config**

now the picom is not installing in i3 originally so first download it then put config_picom file
**NOTE: CHANGE THE NAME OF THE CONFIG FILES BACK TO config AS I RENAMED THEM TO DIFFRENTIATE BETWEEN THEM**


to control brightness without using sudo,

**sudo usermod -aG video $USER**in my system the keyboard backlit is named as asus::kbd_backlight, to check yours type,

*brightnessctl --l* this will list all the devices

then use 

*sudo brightnessctl --d device_name set desired_brightness* to set the brightness

now as this command uses sudo to edit, edit its write permission in /sys/led/device_name


to set the wallpaper, download the wallpaper in ./Downloads then run,

**hsetroot -full ./Downloads/wall.jpg**
