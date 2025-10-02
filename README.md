# ✨ Project Title:
Smart-Parking-Gate-System
## Objectives:
 • Design a simple parking gate control system using Arduino.
 • Allow the user to open and close the gate with a single push button.
 • Provide clear visual indicators through an LCD display (GO / WAIT / STOP).
 • Use an RGB LED to indicate the gate status (Green for GO – Orange for WAIT – Red for STOP).
 • Practice integrating electronic components (Button, LCD, RGB LED, Servo) with Arduino programming.

 ## Problem:
Many parking lots do not have automated gate control systems, which causes delays in entry and exit, especially during peak hours. Traditional systems are often expensive and complex to install. Therefore, this project was designed to provide a simplified and low-cost model that simulates a smart parking gate using basic electronic components that can be easily implemented by students and beginners.

 ## Hypothesis:
 If the button is pressed the first time, the gate will open, the green light will turn on, and the screen will display “GO”.
When the button is pressed again, the screen will display “WAIT” with a countdown (3–1), the orange light will turn on, and then the gate will close, the screen will display “STOP”, and the red light will turn on.

## Background:
 + Modern parking lots often use automated systems to control entry and exit gates.
 + This project simulates a simplified version of such systems using Arduino and basic electronic components.
 + It is a useful educational application to understand microcontroller programming and integration with sensors and actuators.

 ## Hardware Stack:
 + Arduino UNO
 + Push Button
 + Servo Motor (for gate control)
 + LCD 16x2 Display
 + RGB LED (Red, Green, Orange)
 + Resistors, Jumper wires, Breadboard
 
### Design:
![Design](https://github.com/Anil-dot12/Smart-Parking-Gate-System/blob/8ebbf9e908fc0787e2db71cd3441e8060a309252/Design1.png)

The design connects the button → Arduino → Servo motor + RGB LED + LCD display. 
Synchronization was tested to ensure all indicators (GO / WAIT / STOP) work consistently with the gate movement.
 
## Expected Results:
 1. First button press → Gate opens + LCD shows “GO” + Green light.
  ![Design](https://github.com/Anil-dot12/Smart-Parking-Gate-System/blob/81cfead05f8775638fd63db268d58de6a8c44237/desine2.png)
 2. Second button press → LCD shows “WAIT” with countdown (3–1) + Orange light.
  ![Design]()
 3. After countdown → LCD shows “STOP” + Red light + Gate closes.
    ![Design]()
