# Software Recruitment Package 2022-2023
A skills testing/training task for new applicants to the CanSat software team

## Required Materials
For this task the following components are required:
1. Arduino Uno (Or equivalent microcontroller that can run Arduino code)
2. TMP36 Temperature Sensor
3. 4-Leg RGB LED
4. 3-Pin Servo Motor

If you do not have access to these parts TinkerCAD offers a great circuit simulator that has the capability to simulate an Arduino and Arduino Code.
All of the above components are available in TinkerCAD.

## Task
- The task is to write software for an Arduino such that the RGB LED and Servo Motor will be affected based on the temperature read from the TMP36.
- The Servo Motor should have its angle mapped to the Temp sensor
  - The min/max of the temp sensor should correspond with the min/max angle of the Servo
- The colour of the RGB LED should be set based on this table:

| Temperature Range  | Colour |
|--------------------|--------|
| -40 <= Temp <= -10 | Blue   |
 |  -10 < Temp <= 20 | Green  |
| 20 < Temp <= 50 | Yellow |
| 50 < Temp <= 80| Purple |
| 80 < Temp <= 110| Red    |
| 110 < Temp <= 125| White  |
## Submission
Upon completion of the task please upload all required files to the Google Form in a zip file.  

The required files are:
- .ino file for the Arduino
- A picture of the circuit you built. (Either in TinkerCAD or IRL)