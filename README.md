# Docs
The place for Documentation of all things OpenHAK related

## Getting started with Arduino firmware
To create firmware to upload to your OpenHAK, you'll need to install to correct board files into the Arduino IDE
1. Open the Arduino IDE
2. On a Mac, click on the Arduino menu and select preferences, on PC and Linux, select the File menu and select preferences
3. Find the Additional Boards Managers URLs box and click the icon to the right of it
4. On a new line, paste the OpenHAK boards json: https://raw.githubusercontent.com/OpenHAK/Simblee/master/package_openhak_index.json
5. Click OK
6. Now click the tools menu, mouse over the "Board:" option, then select Boards manager
7. This list should refresh and you'll be able to scroll down until you see the OpenHAK boards listed
8. Click the install button and wait for the install to complete
9. Now you can select the OpenHAK board from the Arduino Boards menu, and compile code for your OpenHAK!


## Getting code on your OpenHAK
The easiest way, that also requires no additional hardware, is to use the OTA DFU method
Find videos and a step by step guide here: https://github.com/OpenHAK/Docs/blob/master/Update%20OpenHAK%20Firmware.md

### Using FTDI
You need a 3.3v FTDI and the OpenHAK accessory cable
Connection guide coming soon!!

