# FPGA_Stopwatch
IEEE Student Branch at UCLA Digital Audio Visualizer (DAV) Project Lab 5 Part D

## Description
This module uses the seven segment displays on the FPGA to create a makeshift stopwatch. The seven segment display serves as the counter of the stopwatch. It should start at 0 and increment by one each second. There is also a reset button that will reset the counter value to 0 and restart the stopwatch when the button is pressed. 

The inputs of the stopwatch module are:
* A 50MHz clock (need to convert to a 1Hz clock using a clock divider)
* A reset button

Proper pin assignments are located in the datasheet for the FPGA. 

### Note
* Please do not copy/use the code if you are currently a DAV member
