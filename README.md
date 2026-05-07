# Smart Radar System using ESP32

## Overview
This project is a real-time object detection and radar visualization system built using ESP32 and HC-SR04 ultrasonic sensor. The system scans surrounding objects using a servo motor and displays distance and angle on an LCD. LED and buzzer alerts are activated when an object comes within a predefined range.

---

## Features
- Real-time distance measurement
- Servo motor-based radar scanning
- LCD display for angle and distance
- LED and buzzer alert system
- Serial output for radar visualization
- Low-cost embedded system project

---

## Components Used
- ESP32
- HC-SR04 Ultrasonic Sensor
- Servo Motor
- 16x2 I2C LCD
- LED
- Buzzer
- Jumper Wires
- Breadboard

---

## Circuit Connections

| Component | ESP32 Pin |
|-----------|-----------|
| TRIG      | D5 |
| ECHO      | D18 |
| Servo     | D4 |
| Buzzer    | D13 |
| LED       | D12 |
| LCD SDA   | D21 |
| LCD SCL   | D22 |

---

## Working Principle
The ultrasonic sensor measures the distance of nearby objects. The servo motor rotates the sensor from 0° to 180° to simulate radar scanning. The ESP32 processes the data and displays the angle and distance on the LCD. If the object is closer than 20 cm, the LED and buzzer turn ON as an alert.

---

## Applications
- Obstacle Detection
- Robotics
- Smart Parking
- Security Systems
- Automation Projects

---

## Technologies Used
- Embedded C / Arduino
- ESP32
- Sensor Interfacing
- Processing (Radar Visualization)

---

## Future Improvements
- WiFi-based monitoring
- Mobile app integration
- Cloud data storage
- AI-based object detection

---

## Author
**Madhu**  
B.Tech Electronics and Communication Engineering  
Central University of Rajasthan
