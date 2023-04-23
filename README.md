# PLC
Analog Tank-Pump Control with Alarms and Notifications
This repository contains PLC code for controlling an analog tank-pump system with alarms and notifications.

Overview
The system consists of a tank with a liquid level sensor, a pump, and a PLC (Programmable Logic Controller). The PLC reads the analog signal from the level sensor and controls the pump to maintain the desired level of liquid in the tank.

In addition, the system is equipped with alarms that trigger when the liquid level is too high or too low.

Code
The PLC code is written in ladder logic and is compatible with Siemens S7-1200 PLC. The code is organized into the following modules:

Main Program: This module is responsible for the overall control of the system. It reads the analog signal from the level sensor, compares it to the desired setpoint, and controls the pump accordingly. It also monitors the status of the alarms and sends notifications via email when necessary.

Pump Control: This module controls the pump based on the output from the Main Program module.

Alarm Management: This module monitors the liquid level in the tank and triggers the appropriate alarms if the level is too high or too low.

License
This code is licensed under the MIT License. Feel free to use and modify the code as needed, but please attribute the original source.
