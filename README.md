# E-Ink-Fallout-Name-Tag
A two-layer PCB designed to mount an E-Ink display powered by an Adafruit RP2040 Feather. Made by apricity as a name badge for Hackclub Fallout.

## Notes:
Through bores are for connecting the Feather board, upon which is an FPC connector for the screen. Ideally, the board mounts on one side and the screen on the other to reduce the profile (since the microcontroller has a slightly smaller length + width footprint, it makes integrating the battery easier). Currently, a case is pending which will cover the back and contain the holder for the 3.7v 100ma lithium polymer battery (the board also functions via USB-C but that's a copout). Mounting hardware for the PCB to the case is planned to be via M2 componenets.

Additionally, there is no current wiring schematic (might add rgb leds if extra time during Fallout? or afterwards) as the board is mainly just to mount and hold components (and of course for aesthetics). The battery and screen plug into the Adafruit RP2040 via STEMMA QT and FPC respectively.

### PCB View
![](/assets/fallout_name_badge.png)

### PCB 3D Top View
![](/assets/fallout_name_badge_pcb_top_view.png)

### PCB 3D Bottom View
![](/assets/fallout_name_badge_pcb_bottom_view.png)
