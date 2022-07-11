# Software Recruitment Package 2022 - 2023

A training task for new applicants to the CanSat software team

## Required Materials

For this task the following components are required:

1. Arduino Uno (Or equivalent microcontroller that can run Arduino code)  
   <img alt="Arduino Uno" src="https://github.com/ryerson-cansat/CanSat_2022-2023_Training_Tasks/blob/main/Software%20Training%20Task/Images/Arduino%20Uno.jpg" width="500"/>
2. TMP36 Temperature Sensor  
<img src="https://github.com/ryerson-cansat/CanSat_2022-2023_Training_Tasks/blob/main/Software%20Training%20Task/Images/TMP36.jpg" alt="Temperature Sensor">
3. 4-Leg RGB LED    
<img src="https://github.com/ryerson-cansat/CanSat_2022-2023_Training_Tasks/blob/main/Software%20Training%20Task/Images/4-Pin%20RGB%20LED.jpg" alt="RGB LED">
4. 1 kΩ Resistor  
<img src="https://github.com/ryerson-cansat/CanSat_2022-2023_Training_Tasks/blob/main/Software%20Training%20Task/Images/1k%20Ohm%20Resistor.jpg" alt="1K Resistor" style="transform:rotate(90deg);"> <br>
5. 3-Pin Servo Motor  
<img src="https://github.com/ryerson-cansat/CanSat_2022-2023_Training_Tasks/blob/main/Software%20Training%20Task/Images/Servo%20Motor.jpg" alt="Servo Motor">

If you do not have access to these parts, TinkerCAD offers a great circuit simulator that has the capability to simulate
an Arduino and Arduino code.
All of the above components are available in TinkerCAD.

## Task

- The task is to write software for an Arduino such that the RGB LED and Servo Motor will be affected based on the
  temperature read from the TMP36.
- The Servo Motor should have its angle mapped to the Temp sensor
    - The min/max of the temp sensor should correspond with the min/max angle of the Servo
- The colour of the RGB LED should be set based on this table:

| Temperature Range  | Colour |
|--------------------|--------|
| -40 <= Temp <= -10 | Blue   |
| -10 < Temp <= 20   | Green  |
| 20 < Temp <= 50    | Yellow |
| 50 < Temp <= 80    | Purple |
| 80 < Temp <= 110   | Red    |
| 110 < Temp <= 125  | White  |

## Submission

Upon completion of the task please do the following:
1. Create a GitHub repository. (Repository can have any name you want)
2. Upload the required files into the repository. (The required files are listed below)
3. Create a README file explaining what your code does and how it works.
4. Include your name in the README
5. Upload the link to your repository in the submission Google Form (LINK)


The required files are:
- .ino file for the Arduino
- A picture of the circuit you built. (Either in TinkerCAD or IRL)