# AVR Motor Controller

## Overview
This repository contains an AVR controller implemented in C for motor speed control and temperature monitoring. The controller utilizes an AVR microcontroller, H-Bridge motor driver, and various sensors to regulate motor speed and detect temperature levels. The project also includes an LCD display for real-time status updates.

## Features
- **Motor Speed Control**: Adjusts the speed of a motor using Pulse Width Modulation (PWM).
- **Temperature Monitoring**: Utilizes an analog temperature sensor to measure ambient temperature.
- **Direction Control**: Manages the direction of the motor using an external interrupt.
- **LCD Display**: Shows real-time information, including motor speed, temperature, and status.

## Hardware Setup
- **AVR Microcontroller**: Utilizes ATmega8 with PWM capability.
- **H-Bridge Driver**: Controls the direction of the motor.
- **Analog Temperature Sensor**: Measures ambient temperature.
- **LCD Display**: Provides visual feedback on motor speed, temperature, and status.

## How to Build and Run
1. Setup the hardware components based on the provided schematic.
2. Use an AVR programmer to flash the controller code onto the ATmega8.
3. Connect the components according to the pin configuration in the code.
4. Compile the C code using an AVR-GCC compiler.
