# SMSAM

## Overview

The Smart Monitoring and Security System for Autonomous Machines is an IoT-based monitoring solution designed to improve machine awareness, operational safety, and environmental monitoring. The system continuously collects real-time data from multiple sensors and provides feedback through a web-based dashboard, visual indicators, audible alerts, and surveillance capabilities.

The project demonstrates how embedded systems and wireless technologies can be integrated to monitor autonomous machine environments and detect potentially unsafe operating conditions.

---

## Features

- Real-time temperature and humidity monitoring
- Motion detection using a PIR sensor
- Obstacle and proximity detection using an ultrasonic sensor
- Ambient light monitoring using an LDR
- Live surveillance using an ESP32-CAM
- Visual alerts through LEDs
- Audible alerts through a buzzer
- Remote monitoring through a web dashboard
- Wireless communication using Wi-Fi

---

## Hardware Components

- ESP32 Development Board
- ESP32-CAM Module
- DHT22 Temperature and Humidity Sensor
- HC-SR04 Ultrasonic Sensor
- PIR Motion Sensor
- LDR Sensor
- LEDs
- Buzzer
- Breadboard
- Jumper Wires
- 5V Power Supply

---

## Software Technologies

### Embedded Development
- Arduino IDE
- ESP32 Board Package
- AI Thinker ESP32-CAM Configuration

### Backend Development
- Python
- Flask

### Database
- MySQL

### Frontend
- HTML
- CSS
- JavaScript
- Bootstrap

---

## System Operation

The system continuously monitors environmental and situational conditions around autonomous machines.

Sensor data is collected and processed by the ESP32 microcontroller. When predefined thresholds are exceeded, the system responds by:

- Activating warning LEDs
- Triggering the buzzer
- Capturing images through the ESP32-CAM
- Sending data to the web dashboard

Users can monitor system conditions remotely through the dashboard interface.

---

## Dashboard Functions

- User Login
- User Registration
- Admin Dashboard
- Real-Time Sensor Monitoring
- Alert Notifications
- Camera Surveillance Feed
- Historical Sensor Data
- System Status Monitoring

---

## Project Structure
