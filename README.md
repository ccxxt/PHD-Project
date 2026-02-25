Miniaturized Multiplexed Force Sensor for Surgical Applications

This repository contains all code developed for the PhD project “Miniaturized Multiplexed Force Sensor for Surgical Applications.”
It includes the full data-acquisition pipeline—from microcontroller firmware to MATLAB scripts for real-time visualization.

PHD-Project/
├── Matlab_getdata_function/   # MATLAB function for receiving data from PCB
├── Matlab_plotData/           # MATLAB scripts for real-time plotting
├── Microcontroller_code/      # Firmware for acquisition PCB
└── README.md

Matlab_getdata_function/
get_data.m
Handles serial communication
Receives and parses raw data packets from the PCB
Matlab_plotData/
Real-time plotting and visualization
Used for experiments, calibration, and debugging

Microcontroller Code
Located in Microcontroller_code/
Includes firmware for:
Sensor multiplexing
ADC sampling
UART/USB data transmission
Timing and synchronization

