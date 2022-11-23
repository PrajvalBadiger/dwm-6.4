# DWM -dynamic window manager

My fork of dwm-6.4


# patches
1. actualfullscreen - super + shift + f
2. alwayscenter - spawn windows at center in floating mode
3. attachbottom - New clients attach at the bottom of the stack instead of the top.
4. bar-height   - Change DWM's default bar height
5. fullgaps - gaps between windows
6. hide-vacant-tags - tags with no windows will not show in the top bar
7. pertag - layouts can be changed per tag
8. swallow - window swallowing 
9. xresources - dwm parameters such as colors, fonts and gaps can be modfified with xresources file
10. xrdb - to reload colors without restarting dwm (super + shift + r)

# installation
``` bash
git clone https://github.com/PrajvalBadiger/dwm-6.4.git
cd dwm-6.4
sudo make clean install
```
