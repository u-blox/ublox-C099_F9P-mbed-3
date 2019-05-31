# C099-F9P mbed OS 3 Application Firmware
The mbed OS 3 application firmware supports developers to operate wireless communication features in C099-F9P.

https://www.u-blox.com/en/product/c099-f9p-application-board

User Guide

https://www.u-blox.com/sites/default/files/C099-F9P-AppBoard-Mbed-OS3-FW_UserGuide_%28UBX-18063024%29.pdf

# RELEASE INFO
File: c099mbed3_v1.2.0.bin

MD5: 106f7a4a212e35604e3478222b6517ad 

Version: 1.2.0

Dependencies: ublox-odin-w2-drivers_v1.3.1.a, mbed OS 3

## DESCRIPTION
The application firmware supports:

- Bluetooth Classic connectivity 
- Bluetooth Serial Port Profile connection
- Wi-Fi 2.4 GHz Access Point and Station
- UDP server and client over a Wi-Fi connection (Base and Rover operation)
- UART and I2C connectivity
- Non-volatile data storage for user settings
- Remote Procedure Calls through a Command Line Interface

## FW UPDATE

Please use the latest available FW to enable all reported features and to ensure board-to-board connectivity.

Command line structure for smt32flash.exe to upload a FW:

.\stm32flash.exe -b 115200 -w <c099mbed3.bin> -S 0x8000000 COM<port number>

## MECHANICAL FILES

- 3D STEP file of Rev B: https://github.com/u-blox/3D-Step-Models-Library/blob/master/POS/C099_RevB.zip

## DISCLAIMER
Copyright (C) u-blox AG

u-blox reserves all rights in this deliverable (documentation, software, etc.,).
