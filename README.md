# X1 EasyThreeD - Board ET4000+ w/ARREY (AT32f4 - STM CLONE) Based on marlin 2.1.2.1

* Using MKS_ROBIN_LITE pinouts 
* Full buttons support 
* PID default setting adjusted
* PWM_MOTOR_CURREN lowered to 0.7
* Linear advance enabled 
  * Arc support disabled to save RAM 
* I don't believe this board has EEPROM, so you must have an SD card inserted to save M500 
 * Make sure to run M502 / M500 after flashing the board 
 * Adjust your e-steps! these extruders can vary wildly from the default 1140 steps per mm (this is the calculator I use - it's very good https://teachingtechyt.github.io/calibration.html#esteps)
 * Bed heater removed (enable back with #define TEMP_SENSOR_BED 1 and uncommenting //#define PIDTEMPBED)


Additional files: 
* Board schematics are in the pdf's (also, for the NANO ET-4000 V2 board, I got these from the manufacturer)
* A working mksLite.bin (flash by adding this file to your SDcard and rebooting)
* My initial Cura profile (X1-V1.curaprofile) for this printer - very early stages!

In general, be careful with 3d printing.
I kept this build as close to the original marlin as I could. 
All the safety features are enabled, but please don't neglect to test your printer! 
* These are some good sources to get you started : 
 * https://youtu.be/VK_K6fp4BIk
 * https://youtu.be/lURxGcdBm9A
 * https://all3dp.com/4/finally-an-official-guide-to-3d-printing-safety/


## Installation 

You can use the bin from the release if you don't want to compile the build https://github.com/muschaw/Marlin-2.1.2.1-For-X1-EasyThreeD/releases/tag/V2
* Power off the printer
* Copy the mksLite.bin on your SD card
* Insert the card into your printer and power it on - the update will take about 10-15 seconds (the LEDs will flash) 





