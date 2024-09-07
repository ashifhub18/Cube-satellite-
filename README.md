CubeSat with AI Object Detection and Environmental Monitoring
This project focuses on the development of a CubeSat prototype featuring AI object detection capabilities and environmental monitoring using onboard sensors. The CubeSat is a miniaturized satellite measuring 4 x 4 x 4 cm and weighing 50 grams. The key objectives of the project are to detect objects in space using an ESP-32 Cam Module and measure temperature and humidity using a DHT11 sensor.

Table of Contents
Introduction
Hardware Components
Software Requirements
Circuit Diagram
Features
Setup and Installation
Usage
Applications
Future Improvements
Contributing
License
Introduction
CubeSats are a subclass of nano-satellites used for research purposes in low Earth orbit. This project develops a CubeSat with AI-powered object detection capabilities, combined with environmental sensing, including temperature and humidity measurement.

The CubeSat uses an ESP-32 Cam Module for object detection and a DHT11 Sensor for environmental data collection. The project is controlled by an Arduino Pro Mini with data logging to a memory card.

Hardware Components
Arduino Pro Mini (ATmega328P)
ESP-32 Cam Module (with onboard AI capabilities)
DHT11 Sensor (for temperature and humidity measurement)
2 Lithium Polymer (LiPo) Batteries (3.7V, 300mAh)
Wires and connectors
Software Requirements
Arduino IDE (for programming the Arduino Pro Mini)
ESP32 Board Package (for ESP-32 Cam Module support)
AI Object Detection Algorithm (running on the ESP-32)
DHT11 Sensor Library (for environmental data)
The DHT11 sensor provides temperature and humidity data, connected to the Arduino Pro Mini.
The ESP-32 Cam Module handles image capture and object detection.
Power is supplied by the LiPo batteries.
Features
AI Object Detection: Using the ESP-32 Cam Module to detect objects in space.
Environmental Monitoring: The DHT11 sensor measures temperature and humidity, storing data on an SD card.
Wireless Data Transmission: Wi-Fi module on the ESP-32 sends data to a mobile IP for real-time viewing.
Setup and Installation
Hardware Setup:
Connect the DHT11 sensor to the Arduino Pro Mini.
Attach the ESP-32 Cam Module to the CubeSat body.
Power the CubeSat using the LiPo batteries.
Software Setup:
Clone this repository:
bash
Copy code
git clone https://github.com/yourusername/CubeSat-AI-Object-Detection.git
Open the Arduino IDE and add the ESP32 Board Package.
Install the required libraries for the DHT11 sensor and ESP-32 Cam Module.
Upload the Arduino code to the Pro Mini and ESP-32 Cam code to the ESP module.
Usage
Power on the CubeSat.
Connect to the Wi-Fi network created by the ESP-32 Cam Module.
Access the live video feed and object detection results via the mobile IP.
Temperature and humidity data will be stored on the onboard SD card.
Applications
Space Research: Object detection and environmental monitoring in space.
Earth Observation: Low-cost imaging and data collection for scientific purposes.
Communications: Test new communication technologies in a low-cost CubeSat setup.
Future Improvements
Implement gyroscopic technology for improved satellite positioning.
Enhance AI object detection algorithms for more accurate identification.
Extend CubeSat's operational capabilities for interplanetary missions.
