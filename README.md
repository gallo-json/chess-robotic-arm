# Robotic Arm for Chess

## Date
I was in 8th grade. 2019.

## What can it do?
User input: The chess piece to move (different sizes, different heights), the square that it is in, and the desired square.
The robot: Moves that piece to the desired square.

## Tech stack & hardware
- Arduino Uno
- SSC-32U Servo controller board
- Lynxmotion AL5D arm
- Arduino C/C++

## How does it work?

The Arduino is connected to the servo controller via TX/RX pins to transmit TTL serial data. The Arduino takes care of all the calculations, user input, etc. All the arm's motors are connected to the servo controller. The Arduino and servo controller are powered speratarely.

Required a lot of diagrams and math to calculate the angles correctly. Here is just one page of my notebook: 
Click here to see the robot in action: link when ready.
   
![arm_picture](https://media.discordapp.net/attachments/660295888563994638/664265594039697426/IMG_0208.JPG?width=880&height=660)