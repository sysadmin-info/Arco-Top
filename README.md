# Arco-Top
conky which displays basic information about the system in one line.

![Screenshot](https://i.imgur.com/HoOUtyb.png)

The theme was modified to adapt it to modern conky configuration requirements.

I took it from ArcoLinux.

Here you have the list of all conkyrs which comes from the ArcoLInux: https://gitlab.com/rzn/arcolinux-conky-collection/-/tree/master/etc/skel/.config/conky

Dependencies:
* conky
* git to clone the resource
* Also, download and install Droid Sans font. https://www.fontsquirrel.com/fonts/droid-sans

Instruction:
* open terminal
* type: cd .conky
* type: git clone https://github.com/sysadmin-info/Arco-Top.git
* type: cp conky-delay.sh ~/
* type: cd ..
* type: chmod +x conky-delay.sh
* run conky delay script by typing ./conky.delay.sh
* add conky-delay.sh script to autostart to let it start after the login.
