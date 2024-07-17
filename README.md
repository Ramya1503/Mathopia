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

## How It Works
### 1.Keypad Input: 
  - The 4x4 keypad allows users to input numbers (0-9) and operations (A-D). Each button press is read by the Arduino.

### 2.LCD Display: 
  - The 16x2 LCD display shows the current input from the keypad and the results of the calculations.

### 3.Buzzer Feedback: 
  - The buzzer provides auditory feedback for correct and incorrect inputs.

### 4.Potentiometer: 
  - The potentiometer is used to adjust the brightness of the LCD display.

## Wiring
  
  - **Keypad:** Connect the keypad to digital pins 2-9 on the Arduino.

  - __LCD Display:__ Connect the LCD to digital pins 10-13 and analog pins A0-A1.

  - **Buzzer:** Connect the buzzer to digital pin 11.

  - **Potentiometer:** Connect the potentiometer to the LCD's V0 pin to control contrast.

## Software
### Libraries
  To install the necessary libraries:

            - #include <LiquidCrystal.h>
            - #include <EEPROM.h>

## Usage
  1. Connect all components as per the wiring diagram.
  2. Upload the provided code to the Arduino.
  3.Use the keypad to input numbers and operations.
  4.Observe the results on the LCD and listen for the buzzer feedback.
  5.Reset the Arduino to see the last key pressed displayed on the LCD.

## Conclusion
  The Mathopia project demonstrates the versatility and power of combining various electronic components with an Arduino microcontroller. By integrating a keypad, LCD display, buzzer, potentiometer, we created an interactive and educational math game. This project not only enhances programming and electronics skills but also provides a foundation for more advanced projects. Future improvements could include implementing mathematical operations, enhancing the user interface, and adding additional interactive features. Mathopia showcases how creativity and technology can come together to create engaging and practical applications.
