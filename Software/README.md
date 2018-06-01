# EduBOT Software

## General

Edubot.h implements PID speed control on both motors, optimized
for the Bot marked "1". It uses timer 2 on the arduino for sampling.
Edubot.h also has functions to move EduBOT at a constant linear speed,
or to move EduBOT a certain angle in degrees.

LibSonar and LibMotor contain classes that interface with the on-board
sonars and motors on the arduino.

Both are in development, and will be constantly updated.

## Installing
Clone this folder into your Arduino/libraries directory. (Or download
as ZIP and extract)

## Getting Started
To get started, we suggest opening the edubotExemplo example inside the
Edubot library. It contains examples of all basic functions and can be 
used as a model for your program.
