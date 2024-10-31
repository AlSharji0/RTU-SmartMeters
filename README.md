Smart Meter Simulation - Modbus RTU Manipulation Research
Description
This project demonstrates a simulated environment for analyzing vulnerabilities in legacy Modbus RTU-based smart meters. It simulates communication with Modbus RTU devices, enabling data manipulation in a controlled, research-focused environment. This project is intended for cybersecurity research, educational purposes, and controlled testing environments only.

Purpose
The goal of this project is to study potential vulnerabilities in legacy smart meters deployed from 2018 to 2020, which often lack advanced security measures like secure boot, encrypted firmware, or secure firmware updates. Analyzing these vulnerabilities in a controlled environment can contribute to identifying and mitigating risks within critical infrastructure.

Features
Establishes simulated Modbus RTU communication with legacy smart meters.
Demonstrates data manipulation techniques within a simulated setup.
Calculates and appends CRC16 checksums to Modbus frames.
Provides insight into how unprotected devices could be manipulated in real-world scenarios.
Important Note
This code is intended for research and educational use only. Do not use this code for unauthorized access, manipulation of real-world devices, or any activities outside ethical, simulated environments.

Disclaimer
DISCLAIMER: This project is intended solely for educational and research purposes. Unauthorized use of this code against real devices or networks is prohibited and may violate local and international laws. The authors and contributors are not responsible for any misuse or damage caused by this code outside the intended research context. All testing should be conducted in controlled, simulated environments.

Requirements
Windows operating system
Visual Studio or any compatible C++ compiler
Access to a Modbus RTU simulator or emulation tool (if desired for testing)
Usage Instructions
Setup: Install necessary dependencies for serial communication on Windows.
Compile: Compile the project using Visual Studio or a compatible C++ compiler.
Simulated Environment Only: Run this code strictly in a simulation environment.
Configure COM Port: Update the COM port (L"COM3") to match your local setup for serial communication.
Code Overview
GetSerialHandle: Initializes and configures the serial port for communication.
CRC16: Calculates CRC16 checksums for the Modbus frame to maintain data integrity.
manipulate: Demonstrates manipulation of simulated meter data.
main: Runs a loop to communicate with the simulated device, modifying and re-sending altered data.
