# LED Matrix Cube controlled by FPGA

### Pipeline

LED Matrix Using FPGA  |  Feasibility  |  Advantages  |  Disadvantages  |
---------------------- | ------------- | ------------ | --------------- |
FGPA                   | Long lines of repetitive code can be difficult for everyone working with it| Low power consumption, can be changed according to user needs| Confusing to Multiplex even with experience
LED Matrix Array       | Hard to connect 512 LED's in a neat pattern | Looks Absolutely stunning, and can make different patterns | Single LED Failure can cause problems in rewiring the LED |
Transistors power supply  | Easy to use and Highly cost effective, difficult to manage 64 transistors at once | Brightens the LED by supplying more power and less affected by multiplexing | High voltage can cause LED burnout, Low voltage Cause lesser brightness, need to find optimal spot
Multiplexing | Greatly reduces the number of connections needed to control LED | Easy to control if grasp of concept is present | LEDs get dimmer as it runs through duty cycles|

### Improvements
Brightness can be increased by calculating the least amount of LED which is powered on in the certain duty cycle in a certain row, an boosting voltage to the maximum supported in the least one.

FGPA can be replaced with Arduino Mega, which has adequate pins and easier to program than FPGAs.

# Quadruple Legged Arduino Bot

### Pipeline
4-Legged Arduino Bot   |  Feasibility  |  Advantages  |  Disadvantages  |
---------------------- | ------------- | ------------ | --------------- |
Arduino | Difficult to simulate the movement of locks for all directions, each has to be made into a loop and used as functions | Easier than FPGA and Raspberry-Pi, only need knowledge on C | Arduino may not be able to store all the code inside the microcontroller, if coded in lengthy way
Servo Motors | Lot of Servo Motors, difficult to manage | Gives a variety of motions to each leg, and overall increases the movement | 12 servo motors can cause battery run out fast.
Bluetooth | Easy to connect with premade apps | Only a few lines of code to connect functionality with input, longer range than IR sensor | Lesser range than Wi-Fi Module
Motor Drivers | Easy to control, but lot to manage 6 drivers at once | Works on smaller scales of Voltage and current, Variety of options available | 6 Motor Drivers can generate a lot of heat

### Improvements
Bluetooth and Arduino can be switched out with ESP-32, it has a higher memory and Wi-Fi capabilities, and comes around the same cost. It is more efficient, much faster clock speeds
