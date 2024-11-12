# Smart Meter Simulation - Modbus RTU Manipulation Research

## Description
This project demonstrates a simulated environment for analyzing vulnerabilities in legacy Modbus RTU-based smart meters. It simulates communication with Modbus RTU devices, enabling data manipulation in a controlled, research-focused environment. This project is intended for **cybersecurity research, educational purposes, and controlled testing environments only**.

## Purpose
The goal of this project is to study potential vulnerabilities in legacy smart meters, which often lack basic security measures such as encryption and signing of firmware updates & firmware encryption.

## Features
- Establishes simulated Modbus RTU communication with legacy smart meters.
- Demonstrates data manipulation techniques within a simulated setup.
- Calculates and appends CRC16 checksums to Modbus frames.
- Provides insight into how unprotected devices could be manipulated in real-world scenarios.

## Disclaimer
> **DISCLAIMER**: This project is intended solely for educational and research purposes. Unauthorized use of this code against real devices or networks is prohibited and may violate local and international laws. The authors and contributors are not responsible for any misuse or damage caused by this code outside the intended research context. All testing should be conducted in controlled, simulated environments.

## Requirements
- Windows operating system
- Visual Studio or any compatible C++ compiler
- Access to a Modbus RTU simulator or emulation tool (if desired for testing)

## Usage Instructions
1. **Setup**: Install necessary dependencies for serial communication on Windows.
2. **Compile**: Compile the project using Visual Studio or a compatible C/C++ compiler.
3. **Simulated Environment Only**: Run this code strictly in a simulation environment.
4. **Configure COM Port**: Update the COM port (`L"COM3"`) to match your local setup for slave communication.

## Code Overview
- `GetSerialHandle`: Initializes and configures the serial port for communication.
- `CRC16`: Calculates CRC16 checksums for the Modbus frame.
- `manipulate`: Demonstrates manipulation of simulated meter data.
- `main`: Runs a loop to communicate with the simulated device, modifying and re-sending altered data.
