usbasp_Gizduino_minUSB
======================

USBasp firmware source has been modified for Gizduino USB mini

This program turns the Gizduino USB mini into a USBasp so it can program other Atmel devices via the 6-pin ISP connector.

1. To upload this program, insert the jumper to J2 connector and press the reset button.
2. Assuming you have AVRDude installed in your PC, run the flash.cmd from a command shell opened in the firmware folder.
3. Remove the jumper from J2.
4. Attach an ISP cable from the 6-pin header on the Gizduino USB mini to the Arduino board you wish to program. 
5. From the Arduino IDE, select USBasp as programmer.
6. Upload your program using the upload using programmer menu item.
