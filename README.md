# Smart Home Automation Using Arduino

## Overview
This project is a **Smart Home Automation System** designed to control lights, fans, doors, and security alerts automatically using **Arduino Uno** and multiple sensors.  
It focuses on **energy efficiency**, **security**, and **real-time feedback** by automating appliances based on environmental conditions and motion detection.

## Problem Statement
Traditional home systems require manual operation of lights, fans, and doors, which leads to:
- Inconvenience  
- Energy waste  
- Lack of security  

A smart, sensor-based automation system solves these issues efficiently.

## Objectives
- Automate control of home appliances using sensors  
- Integrate **PIR**, **LDR**, **Gas Sensor**, and **Ultrasonic Sensor**  
- Improve **energy efficiency** and **home security**  
- Provide **real-time system feedback**
  
## Hardware Components
- Arduino Uno  
- PIR Motion Sensor (for motion detection)  
- LDR Sensor (for light intensity)  
- Gas Sensor (for safety)  
- Ultrasonic Sensor (for distance measurement and door automation)  
- Relay Module (for controlling AC appliances)  
- Servo Motor (for door control)  
- Buzzer & LEDs (for alerts)  

##  Software Requirements
- Arduino IDE  
- Tinkercad (for simulation)  
- Embedded C programming  
- USB drivers for Arduino  

## Circuit Diagram
*(Refer to `Circuit_Diagram.png` in this repo — from PPT)*

**Working:**
1. **LDR Sensor** detects light intensity to turn **lights ON/OFF**.  
2. **PIR Sensor** detects motion to control **fans/lights**.  
3. **Gas Sensor** triggers buzzer when harmful gas is detected.  
4. **Ultrasonic Sensor + Servo Motor** automate the door.  
5. **Relay Module** switches AC appliances.

##  Code
The full Arduino code is provided in `Smart_Home_Automation.ino`.

Key functionalities:
- Light control using LDR  
- Motion-based fan/light control using PIR  
- Gas leak detection with buzzer alerts  
- Automatic door control with ultrasonic sensor and servo motor  

## Output Examples
- Lights turn ON/OFF based on motion and light level  
- Servo door opens automatically when someone approaches  
- Gas sensor triggers buzzer alert  
- Fan turns ON when motion is detected
  
## Future Enhancements
- IoT integration for remote monitoring  
- Mobile app control  
- Temperature-based fan speed control  
- Integration with voice assistants  

##  References
- [Arduino Official Website](https://www.arduino.cc/)  
- [Tinkercad Circuits](https://www.tinkercad.com/)  
- IEEE Smart Home Research Papers
- PROJECT LINK:https://www.tinkercad.com/things/gThsNBIdqrn-smart-home-automation-sabarish/editel?returnTo=https%3A%2F%2Fwww.tinkercad.com%2Fdashboard%2Fdesigns%2Fcircuits

##  Author
**Kiruthick Sabarish S**    
Email:sabarishkruthick@gmail.com
contact:9384776342
