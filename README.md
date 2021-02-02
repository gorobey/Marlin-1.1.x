# Geeetech A20 Marlin-1.1.x Bugfix
 
This is a firmware update for my Geeetech A20:

Motherboard version: GT2560 V.4.0
Stepper driver: TMC2208
Dispay: LCD12864
Motors: Nema 17, 42 N/cm 1.5A
Estrusion method: Direct drive 

This release is based on Marlin 1.1.x bugfix. (code name: Goro.Arms)

Prebuild firmware is located at this path: .pioenvs/megaatmega2560/firmware.hex

This Firmware version contains various changes:

    - Disable endstop Z min (only works with blotouch installed)
    - Union of babystaps and Z-offset
    - FAST_PWM_FAN enable
    - Auto bed levelling grid 4x4, 3 probe for point (but I used it only for debug via console, I don't use auto bed auto correction during the print)
    - Faderate / Acceleration / Jerk / Linear Pressure Control
    - Lite menu
    - No filament sensor
    - Hardcoded custom scripts and varius routine
    - And more...

Please inspect Configuration.h and Configuration_adv.h for more datails!

Remenber: This program comes with absolutely no warranty:
Works perfectly on my A20, but is modded (I converted it to direct drive and some improvements to the chassis)

Thingiverse project page:
https://www.thingiverse.com/thing:4744713