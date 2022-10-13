# a4988-blind-sensor.-
Fork of nidayand &amp; pgote's Blind project to use the A4988 driver, and the 28BYJ-48 12V motor shorted to be bilinear for greator torque. 


BOM:

- 1x 28BYJ-48 Stepper Motor 12V
- 1x A4988 Stepper Motor
- 1x Nodemcu (esp8266)
- 1x Buck Converter (12v to 5V for the nodemcu.)
- STL's from thingiverse: https://www.thingiverse.com/thing:2392856 

Connecting the 287BYJ-48 wires to an A4988 driver.
 - Orange = 1B
 - Yellow= 2A
 - Pink= 1A
 - Blue= 2B
 - Red: cut off.

- Connect the Step, and DIR, pins on the A4988 driver to the D3 and D4 pins on your NodeMCU.  
- Vmicro & Grnd pins should be connected to the + and - availible on your NodeMCU
- VMotor & grnd should be connected to 12V + and -. 
