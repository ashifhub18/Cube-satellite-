# CubeSat with AI Object Detection and Environmental Monitoring
This repository contains the code and instructions for building a CubeSat prototype equipped with AI object detection and environmental monitoring capabilities. The CubeSat is designed to capture images using an ESP-32 Cam Module, perform object detection, and monitor temperature and humidity using a DHT11 sensor.
## Table of Contents
* Introduction
* Features
* Hardware Components
* Software Requirements
* Setup and Installation
* Usage
* Applications
* Future Work
* Contributing
## Introduction
CubeSats are miniaturized satellites used for research in space. This project builds a small CubeSat prototype (4 x 4 x 4 cm, weighing 50g) that performs object detection using AI and monitors environmental conditions such as temperature and humidity. The project integrates an ESP-32 Cam Module for object detection and a DHT11 sensor for environmental data collection.
## Features
* AI Object Detection: Detects objects in space using the onboard ESP-32 Cam Module.
* Environmental Monitoring: Measures temperature and humidity using a DHT11 sensor.
* Data Logging: Captured data is stored locally on an SD card.
* Wireless Transmission: Object detection results are transmitted via Wi-Fi.
## Hardware Components
* Arduino Pro Mini (ATmega328P)
* ESP-32 Cam Module
* DHT11 Sensor (for temperature and humidity)
* 2 x Lithium Polymer (LiPo) Batteries (3.7V, 300mAh)
* Wires and connectors
## Software Requirements
* Arduino IDE (for writing and uploading code)
* ESP32 Board Package (for ESP-32 Cam Module)
* DHT11 Sensor Library (for Arduino)
* AI Object Detection Model (preloaded on the ESP-32)
* DHT11 Sensor connected to the Arduino Pro Mini.
* ESP-32 Cam Module captures images and detects objects.
* LiPo batteries provide power to all components.
## Setup and Installation
## Hardware Setup
* Connect the DHT11 sensor to the Arduino Pro Mini.
* Attach the ESP-32 Cam Module to the CubeSat body.
* Power the components using LiPo batteries.
## Software Setup
*Clone this repository:
* bash
* Copy code
* git clone https://github.com/yourusername/CubeSat-AI-Object-Detection.git
* Install the Arduino IDE and necessary libraries:
* ESP32 Board Package
* DHT11 Sensor Library
* Upload the respective codes to the Arduino Pro Mini and ESP-32 Cam Module.
## Usage
* Power on the CubeSat.
* Connect to the Wi-Fi network created by the ESP-32 Cam Module.
* Access the live video feed and object detection data using the module's IP address.
* Monitor the temperature and humidity values stored on the SD card or transmitted via Wi-Fi.
## Applications
* Space Research: Object detection and environmental monitoring in space.
* Earth Observation: Capturing and analyzing environmental data from low Earth orbit.
* Communication Testing: Testing new communication technologies in a cost-effective CubeSat platform.
## Future Work
* Add gyroscopic sensors for enhanced satellite positioning.
* Improve the AI model for more accurate object detection.
*Extend the CubeSat’s mission capabilities to interplanetary exploration.
