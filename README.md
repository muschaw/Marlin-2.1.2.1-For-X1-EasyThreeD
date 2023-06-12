X1 EasyThreeD - Board ET4000+ w/ARREY (AT32f4 - STM CLONE) Based on marlin 2.1.2.1

* Using MKS_ROBIN_LITE pinouts 
* No touch buttons support (work in progress)
  * It's best to remove the front panel all together with this build, as some of the buttons might trigger G28.
* Linear advance enabled 
  * Arc support disabled to save RAM 
* I don't believe this board has eeprom so you must have an SD card inserted to save M500 
 * Make sure to run M502 / M500 after flashing the board 
 * Adjust your e-steps! these extruders can vary wildly from the default 1140 steps per mm (this is the calculator I use - it's very good https://teachingtechyt.github.io/calibration.html#esteps)
 * Bed heater removed (enable back with #define TEMP_SENSOR_BED 1 and uncommenting //#define PIDTEMPBED)


Additional files: 
* Board schematics are in the pdf's (also, for the NANO ET-4000 V2 board, I got these from the manufacturer)
* A working mksLite.bin (flash by adding this file to your SDcard and rebooting)
* My initial Cura profile (X1-V1.curaprofile) for this printer - very early stages! Have not tested support yet.

In general be carefull as always with 3d printing.
I kept this build as close to the original marlin as I could. 
All the saftey features are enabled, but please don't neglect testing your printer! 
* These are some good sources to get you started : 
 * https://youtu.be/VK_K6fp4BIk
 * https://youtu.be/lURxGcdBm9A
 * https://all3dp.com/4/finally-an-official-guide-to-3d-printing-safety/



