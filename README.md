# Ultrasonic Sensor-Based Smart Assisting Stick

This project aims to develop an assisting stick for visually impaired individuals.

## Table of Contents
- [Introduction](#introduction)
- [Components](#components)
- [Installation](#installation)
- [Usage](#usage)
- [Troubleshooting](#troubleshooting)


## Introduction
The assisting stick uses an HCSR04 ultrasonic sensor to detect obstacles in the user's path. When an obstacle is detected within 20-30 cm the system provides feedback through sound, helping the user navigate safely.

## Components
- HCSR04 Ultrasonic Sensor
- Arduino Uno (or any compatible microcontroller)
- Buzzer
- Battery Pack
- Connecting Wires
- Stick (can be a cane or a custom-built structure)



## Installation
1. Clone this repository to your local machine:
    ```sh
    git clone https://github.com/yourusername/assisting-stick.git
    ```
2. Open the project in your Arduino IDE.


## Usage
1. Upload the provided Arduino code to your Arduino board.
2. Assemble the circuit as well as the hardware system.
3. Power on the device using the battery pack.
4. The device will start detecting obstacles and provide feedback when an obstacle is within the predefined range.

## Troubleshooting
- **Sensor Not Responding**: Check all connections, ensure the sensor is powered, and verify the pins are correctly connected.
- **No Feedback**: Ensure the feedback mechanism is connected properly and functioning.
- **Inaccurate Distance Measurement**: Calibrate the sensor by adjusting the code to account for environmental factors.




