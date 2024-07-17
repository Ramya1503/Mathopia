# Mathopia
  Mathopia is an Arduino-based project that combines a keypad, an LCD display, a buzzer, and a potentiometer to create an interactive math game. Users can input numbers and operations via the keypad, see the results on the LCD, and receive auditory feedback through the buzzer.

## Components Used
  - Arduino Uno
  - 4x4 Keypad
  - 16x2 LCD Display
  - Buzzer
  - Potentiometer
  - Breadboard
  - Connecting Wires

## Circuit Diagram
![Circuit Diagram](Circuit%20Diagram.jpg)
How It Works
Keypad Input: The 4x4 keypad allows users to input numbers (0-9) and operations (A-D). Each button press is read by the Arduino.

LCD Display: The 16x2 LCD display shows the current input from the keypad and the results of the calculations.

Buzzer Feedback: The buzzer provides auditory feedback for correct and incorrect inputs.

Potentiometer: The potentiometer is used to adjust the brightness of the LCD display.

Wiring
Keypad:

Connect the keypad to digital pins 2-9 on the Arduino.
LCD Display:

Connect the LCD to digital pins 10-13 and analog pins A0-A1.
Buzzer:

Connect the buzzer to digital pin 11.
Potentiometer:

Connect the potentiometer to the LCD's V0 pin to control contrast.
Software
