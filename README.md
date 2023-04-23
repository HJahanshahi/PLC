# PLC
Analog Tank-Pump Control
This repository contains PLC code for controlling an analog tank-pump system.

Overview
The system consists of a tank with a liquid level sensor, a pump, and a PLC (Programmable Logic Controller). The PLC reads the analog signal from the level sensor and controls the pump to maintain the desired level of liquid in the tank.

Code
The PLC code is written in ladder logic and is compatible with different PLCs. The code is organized into the following modules:

Main Program: This module is responsible for the overall control of the system. It reads the analog signal from the level sensor, compares it to the desired setpoint, and controls the pump accordingly.

Pump Control: This module controls the pump based on the output from the Main Program module.

Usage
To use this code, you will need a PLC and the associated programming software for your PLC. You will also need to connect the PLC to the tank, level sensor, and pump.

Once you have the hardware set up, you can download the PLC code to the PLC and run it. The code will automatically control the pump and monitor the liquid level in the tank.

License
This code is licensed under the MIT License. Feel free to use and modify the code as needed, but please attribute the original source.
