This keeb created by a group of people who loves keyball.

Special Thanks to: <br>
PCB: *[yangxing844](https://github.com/yangxing844)* <br>
Case: *[delock](https://github.com/delock)* <br>
Firmware: *[Amos698](https://github.com/Amos698)* <br>

# XCMKB session
Thanks for the above contribution and *[inorichi](https://github.com/inorichi/zmk-pmw3610-driver)* too.

## Quick Link
[Keymap Editor](https://nickcoutsos.github.io/keymap-editor/) <br>
[Github and Keymap Editor Setup](https://github.com/superxc3/zmk_config_sofle#steps) <br>

## Trackball Layer
1. Mouse: Layer 4
2. Scroll: Layer 5
3. Snipe: Layer 6 (cursor moves super slow for precision)

## Trackball Configuration
1. To change the Scroll Layer, go to `zmk-config-Keyball61/config/boards/shields/keyball61/keyball61_right.overlay`: [scroll-layers=5](https://github.com/superxc3/zmk-config-Keyball61/blob/e7d3e26597f22324cf7e9b96c2aa8b27465a058a/config/boards/shields/keyball61/keyball61_right.overlay#L65). Change the number 5 to your preferred layer.
2. To change the defaul CPI, go to `zmk-config-Keyball61/config/boards/shields/keyball61/keyball61_right.conf`: [CONFIG_PMW3610_CPI=1200](https://github.com/superxc3/zmk-config-Keyball61/blob/e7d3e26597f22324cf7e9b96c2aa8b27465a058a/config/boards/shields/keyball61/keyball61_right.conf#L7C1-L7C24). Other trackball config could be changed in the same file too, eg., snipe CPI, scroll direction etc. 

## Suggested Combo
We have added a few combos to the default keymap. Feel free to adjust for your needs. 
![image](https://github.com/user-attachments/assets/58e74a9a-c64d-4339-9fca-f54ced1bdbb2)

