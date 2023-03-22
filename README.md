# MR.2_Robot_Controller
## Description
This program controls the MR.2 robot using an Arduino Mega microcontroller board. It uses various libraries such as Servo, Keypad, LiquidCrystal_I2C, and Wire to interact with the robot's hardware components, including the Two servos for each leg responsible for controlling the robot's movement.<br>
Developed from [Arduino_Mega_Quadruped_Robot_Control](https://github.com/Thanyasit/Arduino_Mega_Quadruped_Robot_Control) <b>2020</b>

## Getting Started
To run this program, you will need an Arduino Mega board and the following hardware components connected to it:

- Two servos for each leg
- Keypad module
- LiquidCrystal_I2C module

## Installation

1. Install the Arduino IDE on your computer.
2. Clone or download this repository to your local machine.
3. Open the MR2_Robot_Controller.ino file in the Arduino IDE.
4. Compile and upload the code to your Arduino Mega board.
## Usage

1. Connect the hardware components to the Arduino Mega board as per the instructions.
2. Power on the Arduino Mega board and the MR.2 robot.
3. Use the keypad to enter the desired command (1-*) all of keypad for the MR.2 robot.
4. Watch as the robot moves according to the command entered.
## Command List

1. Command 1: SetStand>Walk Forward>SetStand
2. Command 2: SetStand>Jog
3. Command 3: SetStand>Walk Backward>SetStand
4. Command 4: SetStandb>Walk Forward>SetStandb
5. Command 5: SetStandb
6. Command 6: SetStandb>Walk Backward>SetStandb
7. Command 7: SetStandb>SetStand
8. Command 8: SetStandbj>jump>SetStandj
9. Command 9: Setstandjk
10. Command A: Sit
11. Command B: Setstand
12. Command C: Setstandhigh
13. Command D: Standdog
14. Command *: Setstandc>Squar Forward>Setstandc
15. Command 0: Setstandc
16. Command #: Setstandc>Squat BackwardSetstandc
