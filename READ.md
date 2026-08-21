# Embedded Systems Internship

## Task 1: Push Button Counter

### Objective
To design and simulate a simple embedded system using Arduino Uno that counts the number of times a push button is pressed and displays the count on a 16×2 LCD.

### Components Used
- Arduino Uno
- Push Button
- 16×2 LCD Display
- 10kΩ Potentiometer
- Jumper Wires

### Pin Connections

| Arduino Uno | Component |
|---|---|
| D2 | Push Button |
| D7 | LCD RS |
| D8 | LCD E |
| D9 | LCD D4 |
| D10 | LCD D5 |
| D11 | LCD D6 |
| D12 | LCD D7 |
| 5V | LCD VDD |
| GND | LCD VSS |
| GND | LCD RW |
| 5V | LCD A |
| GND | LCD K |
| Potentiometer middle pin | LCD V0 |

### Working Principle
The push button is connected to digital pin D2 of the Arduino Uno. The internal pull-up resistor is used for the button. Whenever the button is pressed, the Arduino detects the LOW signal, increments the counter, and displays the updated count on the 16×2 LCD.

A debounce delay is included in the program to prevent multiple counts caused by mechanical bouncing of the push button.

### Software Used
- Wokwi Arduino Simulator
- Arduino C/C++ programming

### Output
The LCD displays:

Push Counter  
Count: 0

Each button press increases the count:

Count: 1  
Count: 2  
Count: 3  
...

### Result
The Push Button Counter was successfully designed and simulated using Arduino Uno. The button press was detected correctly, the count was incremented, and the result was displayed on the 16×2 LCD.

### Project Status
Completed successfully.
