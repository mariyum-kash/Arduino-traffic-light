# Arduino-Traffic-Light-System
My first Arduino-based traffic light system, programmed in C++ and tested in Tinkercad.

## Project Overview
To explore electronic engineering and become more familiar with electronics, I bought an Arduino board and decided to see how far my creativity and ambition to learn would take me.

In this project, I created a mini traffic light system. To understand how electronic components work and how circuits are assembled, I started by simulating my idea in Tinkercad. I connected three LEDs to the Arduino's digital output pins (8, 9 and 10), each with a 330-ohm resistor, and connected them to GND to complete the circuit. 

With some basic knowledge of C, I learned how C++ is used for microcontroller programming, and wrote my own code to control the circuit's sequence in Tinkercad.

This circuit follows a simple sequence: the red LED turns on for 5s. It then stays on for another 2s with the yellow LED. After the first 7s, the red and yellow LEDs turn off, followed by a green LED turning on for a 5s. This green LED then turns off, and the yellow LED turns on for an additional 2s, before the loop restarts.

## Components Used
- ELEGOO UNO R3 
- 3 Resistors (330 ohms)
- 3 LEDs (red, yellow, green)
- USB Cable
- Breadboard
- Jumper Wires
