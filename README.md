# Automatic-curtain-opener-IOT
IoT-based automated curtain opener using NodeMCU ESP8266, DC motor, L298N motor driver, limit switches, MIT App Inventor, and Fusion 360 CAD design.


# Automatic Curtain Opener – IoT Smart Blinds System

This project is an IoT-based automated curtain/blinds opener developed as part of an induction task for the Underwater Robotics Interest Group. The system enables wireless control of vertical blinds using a NodeMCU ESP8266, DC motor, L298N motor driver, limit switches, and a mobile app built using MIT App Inventor.

The curtain can be opened, closed, or stopped using manual buttons in the mobile app. Voice command support is also included through the SpeechRecognizer component. The NodeMCU creates its own Wi-Fi access point and hosts a web server, so the system can work without depending on an external router.

The project also includes CAD design work using Autodesk Fusion 360 for modelling the mechanical casing, rail, joints, and motor-support structure.

## Features

- Wireless control using NodeMCU ESP8266 as a Wi-Fi access point
- Mobile app control using MIT App Inventor
- Voice command support through SpeechRecognizer
- Motor control using L298N motor driver
- Limit switches for safe stopping at fully opened and fully closed positions
- Compact CAD-designed casing and rail mechanism
- Can be extended with sensors or smart home platforms

## Tools and Technologies Used

### Hardware
- NodeMCU ESP8266
- 12V DC Motor
- L298N Motor Driver Module
- Limit Switches
- Jumper Wires
- External 12V power supply

### Software
- Arduino IDE
- MIT App Inventor
- Autodesk Fusion 360

### Concepts
- IoT-based automation
- Embedded systems
- Motor control
- Wi-Fi web server
- Voice-controlled mobile interface
- CAD modelling and motion simulation

## Working Principle

1. The NodeMCU ESP8266 creates a Wi-Fi hotspot.
2. The user connects the mobile phone to this hotspot.
3. The mobile app sends HTTP GET requests to the NodeMCU.
4. The NodeMCU receives commands such as `/open`, `/close`, and `/stop`.
5. Based on the command, the L298N motor driver controls the DC motor direction.
6. Limit switches detect the end positions and stop the motor automatically to prevent mechanical damage.

## My Contribution

My primary contribution was the electronics part of the project. I worked on understanding and documenting the NodeMCU ESP8266-based control system, motor driver connections, limit switch integration, power supply design, and overall hardware working logic.

I also contributed to the overall project integration and testing of the automated curtain opener system.

## Team Members

- Anton Ouseph - Electronics Part
- Pamidipati Srimukha Raja Sarma - Software Part
- Joe J Thannickamattam - CAD Design Part

## Project Context

Completed as part of an induction task for the Underwater Robotics Interest Group.

## Future Improvements

- Add light sensors for automatic curtain control based on ambient light
- Add scheduling support
- Integrate with platforms like Blynk, Home Assistant, or Google Assistant
- Improve casing design for better real-world installation
- Add manual override support

## Status

Prototype-level project completed and documented.
