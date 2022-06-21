# MiniTask 1

## Projects
    LED Matrix Cube confrolled by FPGA
    8-bit Arithmetic Logic Unit
    Quadruple legged arduino bot
    Automatic paper cutter with A.I on Raspberry-Pi
    Game-Server on Raspberry-Pi
    
## LED Matrix Cube confrolled by FPGA
        A 8x8x8 led cube matrix, (or a 4x4x4 for the ease of construction) can be made and can be controlled by FPGA. This LED can be 
    continuously patterned to give continuous wave-like, explosion-like flickering.
    
        This is achieved by manually coding the FPGA in machine language, and turning off and on the individual LED with multiplexing
    and LED drivers. Much larger LED cube Matrix can be made, but feasibility and visual effect is optimal for 8x8x8 cube, which uses a 
    astounding 512 individual LEDs, a 10x10x10 uses a 1000 LEDs, which sounds cool, but connecting them together can be a lot difficult.
![LED Cube](https://user-images.githubusercontent.com/107306498/174750124-3a4baf9f-ba5f-4016-a922-8228c46b2e48.gif)

## 8-bit Arithmetic Logic Unit

        8-bit ALU is a mini computer with far less processing power, only capable of doing basic Arithmetic operations one at a time. 
    This Project can either be done with FPGA's or with the aid of simple AND, OR, NOR, NAND, NOR GATES, Shift registers and Flip-Flops.
    This is also the basic in learning Computer logic.
    
        Input is usually given through DIP Switch SPST in form of binary input, and the output is given out as binary, which can be
    converted into decimal, and displayed on 7 segment display, using CD4511 and
    
![8-Bit ALU](https://user-images.githubusercontent.com/107306498/174746794-a785939d-b23e-4487-8f39-d8683f409a15.png)
![Ben Eater 8 Bit computer](https://user-images.githubusercontent.com/107306498/174771160-0031b402-66e7-4a22-8e69-f9a7fc5702ae.png)


## Quadruple legged Arduino bot
        This bot can manuver through rough terrains, slopes, harsh conditions, the 4 leg mechanism allow movement along all 4 
    directions, and also allows the body to rotate about its center. It is controlled by 12 servo motors, 3 for each leg, giving it
    highly unrestricted movement.
    
        Each Leg is controlled by 12 servo motors, Two control the length and height of the leg, and one controls the rotation of arm, 
    or the movement responsible for the pushing the robot in the right direction. This robot is connected to HC-06 and can be controlled
    with mobile. Or if for a longer range, a RC transmitter can be used to send data to reciever which is connected to bot.
    
![Arduino Spidey](https://user-images.githubusercontent.com/107306498/174747199-84321018-084b-413e-a3f9-60e0b075521f.gif)

## Automatic paper cutter with Machine Learning on Raspberry-Pi
        Auto matic paper cutter uses Machine learning models, and cuts through the outline printed on the paper with precision, it is 
    controlled by 3 stepper motors, two control the position, one control the angle of the blade and a few grippers, which makes sure 
    paper doesn't move out of place. This can be useful to people doing paper craft projects, and pepakura.
    
        The original file is uploaded into the Raspberry pi and the printed paper is placed on the culling platform. The software
    analyses the outermost outline or the required lines, and executes the cuts with the help of stepper motors. The grippers are 
    preferable made out of smooth steel curved surfaces, which does not harm paper, grips paper to culling surface and not to the 
    stepper motors.
![FZYSB3CJG74WKG5](https://user-images.githubusercontent.com/107306498/174749227-920b02a2-ab24-4abd-b26a-b9f437108bab.png)


## Game-Server on Raspberry-Pi
        Raspberry-Pi is a microcomputer with a Mobile ARM Architecture CPU and also come with upto 8 GB RAM, this can be used to host 
    servers for some AAA, indie games like Minecraft, Assault Cube, Terraria, This can come in handy, as a 8 GB Ram server can come
    upwards of 1500 Rs per month. The same cost for a 6 months comes upto the price of installation of the Raspberry-Pi server. 
    Maintenance is minimum in case of Raspberry-Pi servers.
    
        The server files must be installed onto the raspberry pi with the required service files. A Micro-SD card with atleast 8GB must
    be used to store files, and save game files, if any. Redundant power supply must also be given in order to avoid any crashes when
    the server is on.
![RPi Minecraft Server](https://user-images.githubusercontent.com/107306498/174768741-681b8ffe-d1ec-425b-9f37-8d47b44ef0c1.png)
