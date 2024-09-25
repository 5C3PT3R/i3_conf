This repo has the config files to customize your i3

the config files should be replaced in paths as follows

**config = ./.config/i3/config**
**config2 = ./.config/i3statusbar/config**

now the picom is not installing in i3 originally so first download it then put config_picom file
**NOTE: CHANGE THE NAME OF THE CONFIG FILES BACK TO config AS I RENAMED THEM TO DIFFRENTIATE BETWEEN THEM**


to control brightness without using sudo,

**sudo usermod -aG video $USER**


to set the wallpaper, download the wallpaper in ./Downloads then run,

**hsetroot -full ./Downloads/wall.jpg**
