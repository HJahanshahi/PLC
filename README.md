# PLC
PID Heater Control (Analog) with Notifications and Alarm
This repository contains PLC code for controlling an analog heater system using PID control with notifications and alarms.

Overview
The system consists of a heater, a temperature sensor, and a PLC (Programmable Logic Controller). The PLC uses a PID algorithm to control the heater to maintain the desired temperature, and it sends notifications and alarms if the temperature deviates from the setpoint.

Code
The PLC code is written in ladder logic and is compatible with different PLCs. The code is organized into the following modules:

Main Program: This module is responsible for the overall control of the system. It reads the analog signal from the temperature sensor, compares it to the desired setpoint, and controls the heater using the PID algorithm. It also sends notifications and alarms if the temperature deviates from the setpoint.

PID Control: This module implements the PID algorithm to control the heater based on the output from the Main Program module.

Notifications and Alarms: This module sends notifications and alarms if the temperature deviates from the setpoint.

Usage
To use this code, you will need a PLC and the associated programming software for your PLC. You will also need to connect the PLC to the heater and the temperature sensor.

Once you have the hardware set up, you can download the PLC code to the PLC and run it. The code will automatically control the heater using the PID algorithm and monitor the temperature. It will also send notifications and alarms if the temperature deviates from the setpoint.

License
This code is licensed under the MIT License. Feel free to use and modify the code as needed, but please attribute the original source.
