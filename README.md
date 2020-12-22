
# Marlin Firmware for MY Modded 3D printers

<img align="right" width=175 src="buildroot/share/pixmaps/logo/marlin-250.png" />

:rotating_light::rotating_light::rotating_light:  CAUTION :rotating_light::rotating_light::rotating_light:

 This is a **highly modded firmware** for **my personal printers**.
 and probaly will **not work for your printer** without changes.

_I'm not responsible if your printer catches fire :fire:_

So... use and support the original [Marlin](https://github.com/MarlinFirmware/Marlin)



## My Modded Printers (Hardware)
### Sapphire PRO
 - [Belt Tensioner](https://www.thingiverse.com/thing:3969752)
 - [Pulley mount](https://www.thingiverse.com/thing:3982521)
 - [Bed Strain Relief](https://www.thingiverse.com/thing:3982779)
 - [Head Cable Holder](https://www.thingiverse.com/thing:4200631)
 - [Enclosure](https://www.thingiverse.com/thing:3927305)
 - Tempered Glass Bed (6mm)
### Bluer
 - Tempered Glass Bed (4mm)
### Both have:
 - V6 Hotend
 - [V6 Mount](https://www.thingiverse.com/thing:4627176)
 - V6 Heatsink fan on E1
 - BLtouch
 - TMC2209 on XYZE w/ UART

## Marlin notable config changes for my custom printers
### on Configuration.h
  - Vars for each Printer ${PRINTER_NAME}_MOD allowing to enable/disable certain features and values.
  - Serial ports
  - PID (bed/end)
  - XYZ plugs
  - E-steps
  - Bed size
  - Preheat Menu: ABS, PETG, PLA
  - Enabled:
    - S-Curve
    - BLTouch
    - Filament Sensor
    - Auto ABL restore after G28
    - EEPROM save
    - Noozle park
    - SD support
    - SD check
    - Color ui
    - Touchscreen


### Configuration_adv.h
 - Hotend fan on/off
 - TMC Motor Current
 - TMC StealthChop on XYZE
 - Color UI custom colors
 - TMC UART pin config
