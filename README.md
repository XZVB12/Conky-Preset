# Conky-Manjaro-Linux-Edition
#### English description
My conky preset for Manjaro Linux.  
The author of the idea and the first version of Belyakov Igor aka OldHank.

#### Changes:
* Сompletely redesigned project
* Extended functionality
* Fixed values are changed to variables to work correctly on most systems without changing the code. (e.g. host name, distribution name, version, DE name)

#### Installation:
* Copy project files (conkyrc and folders) to the $HOME/.conky/ARCH-V-3/ folder
* Enable using Conky Manager
* Enjoy

#### Note
* Appearance was edited for a screen resolution of 1920x 1080, maybe you will have to make settings for your monitor.
* If it seems to you that the values are updated too often or if too many resources are consumed, increase the value of the `update_interval 0.7 variable`
* If you have more or less than 4 processor cores, you need to duplicate the line `${font StyleBats:size=20}E${font}${voffset -6} CPU4: ${cpu cpu4}% ${alignr} ${cpubar cpu4 6,97} ${voffset 5}` increasing digits for example `${font StyleBats:size=20}E${font}${voffset -6} CPU4: ${cpu cpu4}% ${alignr} ${cpubar cpu4 6,97} ${voffset 5}` for 5 cores. Or comment out unnecessary lines, for example `#${font StyleBats:size=20}E${font}${voffset -6} CPU4: ${cpu cpu4}% ${alignr} ${cpubar cpu4 6,97} ${voffset 5}`
* Lines starting with `#` are comments
* Do not forget to change the name of the network interface

#### TO DO:
* - [ ] Make English version
* - [ ] Deal with fonts
* - [ ] Fix minimizing widget when clicking the "Show Desktop" button
* - [ ] Delete unnecessary fragments

Everything should work without problems, if you have errors let me know.  
All the best.

![Image](https://github.com/XZVB12/Conky-Manjaro-Linux-Edition/raw/master/ScreenShot.png)
