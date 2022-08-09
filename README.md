
# SMART PARKING SYSTEM
Project Description :-
This is a smart parking system which displays the total number of available slots in the parking and it will also show which slot is filled and which is empty.


## Requirements of the Project

1) Arduino Uno
2) Servo Motor
3) 2 Breaboards
4) 5 IR Sensors
5) 16*2 LCD Display
6) Jumper Wires
7) Potentiometer
8) Arduino Ide must be installend in your system
## Important 
Before start making any project promise yourself that you will completed it, no matter how many times you stuck at a particular point.
When you try something which is not in your comfort zone then you will face a lot of issues but that is the most intersting point because  whenever you stuck at something you will find ways to resolve that and when you do so your knowledge will increase and that is the ultimate goal of making the project. 
## Some useful tips

Firstly, understand one thing that project is not the game of one day means you can't make it in one day it takes some time.
Don't try to connect all the components at onces in the starting.
Take small - small steps for example first try to connect Ir sensor to arduino and try to analyse what changes occur in ir sensor light when obstacle comes in front of it .
Now, same goes with the other compontents just like connect servo motor to ardunio and see in which direction it will rotate at a particular angle .
Then try to print something on the Lcd display this will help you to understand the concept of lcd rows and columns.




## Methodology
In this project we are using Aruino Uno, IR sensors , Breadboards,Servo motor, Lcd display and potentio meter.
So the basic structure of the parking will be like - one ir sensor is put at the entry after that servo motor is placed that will do the operation according to the ir sensor means when the ir sensor senses the car than it will checks for the slots availability and opnes up the barrier (servo motor) and after that another ir sensor is placed because it will give instruction to the motor that please close the barrier.
After that we have placed our left over Ir sensors that will senses that in front of which ir sensor car has been parked.











## Pin Confriguation

1) Firstly, we will connect the power rails of the breadborad to the 5v and Ground pin of the Arduino uno.
2) Place or fix the Lcd Display on the breadborad. Lcd dispaly has 16 pins and each pin signifies somethng.

    Lcd Pins Confrigunation
    
    1-> Pin 1  (VDD Pin) is connected to the ground.
    
    2-> Pin 2  (VCC Pin) is connected to the 5v.

    3-> Pin 3  (VEE pin) is connected to the middle pin of the potentiometer. This pin is used to set the contrast (means how much dark or light content shown on the LCD screen) and other two pins of the potentioeter is connected to the 5v and Ground.

    4-> Pin 4  (Register Pin) is connected to the 12 pin of the arduino

    5-> Pin 5  (Read and Write Pin) is connected to the ground.

    6-> Pin 6 is connected to the 11 pin of the arduino .

    7-> Pin 15  (Positive Pin) is connected to 5v.

    8-> Pin 16  (Negative Pin) is connected to the ground.

    This pin 15-16 is responsible for the backlight of the Lcd Display

    9-> Pin 7-14  (Data Pins) these are responsible to send data on the lcd.

        1:- Pin 11 (d4) is connected to the 8 Pin of arduino.
        2:- Pin 12 (d5) is connected to the 7 Pin of arduino.
        3:- Pin 13 (d6) is connected to the 6 Pin of the arduino.
        4:- Pin 14 (d7) is connected to the 5 Pin of the arduino.

3) Now Let's us connect the starting Ir sensor 
    
    Ir sensor has 3 pins VCC,GND,O/P so vcc is connected to the 5v , gnd is connected to the ground and o/p is connected to the 2 pin of the arduino.

4) Connect servo motor

    Servo motor also have 3 pins vcc,gnd,output so connect vcc to 5v , gnd to ground and output pin is connected to 3 pin of arduino.

5) Connect second Ir sensor 

    As we know it has 3 pins so vcc will be connected to 5v , gnd willl be connected to ground and output pin willl be connected to the 4 pin of arduino.

6) Now connect rest of the Ir sensors

    We have 3 ir sensors left and we know that vcc is connected to the 5v,gnd is connected to the ground and output pins of these 3 ir sensors willl be connected to the 13,9,10 pin of arduino.
    

## Images of the project

<img src="https://user-images.githubusercontent.com/87846440/183569304-167becd7-d10c-4d0f-b821-3748af73cc0e.jpeg" height="400"> <img src="https://user-images.githubusercontent.com/87846440/183569450-a5544607-24ec-47f8-8917-7bcb110d8158.jpeg" width="300"> <img src="https://user-images.githubusercontent.com/87846440/183569679-4df20290-b275-4ce4-b1dd-bfd6676af203.jpeg" width="200">


