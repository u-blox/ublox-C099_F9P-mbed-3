# C099-F9P mbed OS 3 Application Firmware
The Mbed OS 3 application firmware supports developers and users to operate the wireless communication features in C099-F9P.

https://www.u-blox.com/en/product/c099-f9p-application-board

User Guide

https://www.u-blox.com/sites/default/files/C099-F9P-AppBoard-Mbed-OS3-FW_UserGuide_%28UBX-18063024%29.pdf

# RELEASE INFO
File: c099mbed3_v2.0.0.bin

MD5: 70f253037d8f877a492494aac73691cd

Version: 2.0.0

Dependencies: ublox-odin-w2-drivers_v1.3.1.a, mbed OS 3

## DESCRIPTION
The application firmware supports:

- Bluetooth Classic pairing
- Bluetooth Serial Port Profile connection
- Wi-Fi 2.4 GHz Access Point and Station
- UDP server and client over a Wi-Fi connection (Base and Rover operation)
- UART and I2C connectivity
- Non-volatile data storage for user settings
- Command Line Interface (RPC syntax)

## FW UPDATE

Use the latest available Mbed FW to enable all the listed features and to ensure board-to-board connectivity.

Prior to FW upload, the ODIN-W2 must be started in safe boot mode.

Refer to the detailed FW upload procedure in the User Guide: https://www.u-blox.com/sites/default/files/C099-F9P-AppBoard-Mbed-OS3-FW_UserGuide_%28UBX-18063024%29.pdf

Command line structure (Windows Power Shell) for stm32flash.exe to upload a FW:

.\stm32flash.exe -b 115200 -w <c099mbed3.bin> -S 0x8000000 COM<port number>

## REVERT TO DEFAULT

To restore the default ODIN-W2 settings:

- press the "ODIN SWITCH0" for more than three seconds and release it
- wait until the NVDS is cleared (approx. two seconds)
- restart ODIN-W2

## MECHANICAL FILES

- 3D STEP file of Rev B: https://github.com/u-blox/3D-Step-Models-Library/blob/master/POS/C099_RevB.zip

## DISCLAIMER
Copyright (C) u-blox AG

u-blox reserves all rights in this deliverable (documentation, software, etc.,).
