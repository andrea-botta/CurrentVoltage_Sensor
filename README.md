# Current and Voltage Sensor
*KiCAD project for a Current and Voltage sensor PCB*
![](docs/pcb_render.png)

This sensor is based around the LTC4151 current and voltage monitor

By deafult a 1.5 mOhm shunt is used, providing a maximum measurable current of 54 A. The voltage range is 7-80 V.  

## Schematic
![[Link to PDF]](docs/schematics.pdf)

## Arduino code
[[Link to Library by Kerry D. Wong]](http://www.kerrywong.com/2014/04/19/arduino-library-for-ltc4151/)

The same link is also available [here](arduino/)

Note that the sensor I2C address can be changes using the solder jumper on the back to change the state of ADR0 and ADR1 to L (Low), H (High) or F (not connected)