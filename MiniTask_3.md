# Debugging
## LED Matrix Cube controlled by FPGA

### Single LED not working
1) Try to manually power it, if LED doesn't work, replace LED
2) Check the code for proper assignment of LED

### Single Row not working
1) Check the LED manually for any short circuits
2) Check connections between Arduino and transistor and LED bulbs
3) Change transistor which is placed to increase current to power LED
4) Check code for any errors

### Entire Layer not working
1) Check Ground connection, thats the only place layer failue can take place physically
2) Check the code, and multiplexing of LED, the certain layer can be unintentionally left out

### LED failing multiple times
1) Reduce the power supplied to the LED
2) If problem persists, change the LED with increased quality.

### Pattern NOT intender as working
1) Check ground connections order with the order in which pins are assigned.
2) Change the order till the right configuration is reached

## Quadruple Legged Arduino Bot

### Module not powering on
1) Check the connections
2) Check the power in battery
3) Check if the board and components are getting power
4) Reupload the code, ensuring the correct format
5) Switch the microprocessor with a new one

### Bluetooth not connecting with Mobile

1) Make sure bluetooth is connected with power, and TX and RX pins are in place
2) Reset the bluetooth module and arduino board
3) Try with a different control app
4) Try with a different bluetooth module

### Robot not moving in intended direction
1) Check the movement of servo motors and compare them with others,If one leg moves much greater than other, increase or decrease power accordingly
2) Check any faulty connections in the servo motors and motor drivers
3) If using two batteries, make sure they are always in same power
