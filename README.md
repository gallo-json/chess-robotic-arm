# Robotic Arm for Chess

## Date


## What can it do?
User input: The chess piece to move (different sizes, different heights), the square that it is in, and the desired square.
The robot: Moves that piece to the desired square.

## Tech stack & hardware
- Arduino Uno
- SSC-32U Servo controller board
- Lynxmotion AL5D arm
- Arduino C/C++

## How does it work?



## Reflection

Challenging project. Needed to learn a bit of Arduino C/C++. Lots of precise diagrams and angles and using trigonomtery to find the exact angles the arm needed to move. Problems arose, like the arm would move too low and not pick up the piece. Another problem was the fact that the trigonometry was wrong, or too many numbers to compute; values were rounded off prematurely and the final angles were off. The code itself is a bit rough but it works.
   
![arm_picture](https://media.discordapp.net/attachments/660295888563994638/664265594039697426/IMG_0208.JPG?width=880&height=660)