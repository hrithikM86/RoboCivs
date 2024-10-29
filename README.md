# RoboCivs - Programmable Robotic Arm

## Overview of the project
RoboCivs is a programmable robotic arm designed to perform specific movements, controlled via a mobile application. This project was developed as part of ITSP at IIT Bombay. 

## Features
- **Mobile-Controlled**: Control the robotic arm through a versatile system linking mobile devices to the robotic arm for specific movements.
- **Servo Motors**: Uses MG996R and SG90 Micro Servo Motors to achieve desired rotations.
- **Microcontroller**: Arduino UNO is used to interface between the Bluetooth module and the mobile network.

## Components
- **MG996R & SG90 Servo Motors**: Implemented to control the rotation of the robotic arm.
- **Arduino UNO**: The microcontroller used for controlling the robotic arm and interfacing with other components.
- **Bluetooth Module**: Enables wireless control of the arm via a mobile application.

## How It Works
The robotic arm's movements are controlled by a mobile application via Bluetooth. Commands from the mobile device are sent to the Arduino UNO, which in turn controls the servo motors to perform the desired motions.

## Installation
1. Clone this repository.
   ```bash
   git clone https://github.com/yourusername/robocivs.git
