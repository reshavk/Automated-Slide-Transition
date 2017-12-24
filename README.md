# Automated-Slide-Transition
Automatic transition of slides by recognising hand gesture using Ultrasonic Sensor and Raspberry Pi

## Requirements
1. Raspberry Pi
2. Ultrasonic Sensor
3. Jumper Wires
4. Bread Board
5. Ethernet Cable

## Libraries Used
1. RPi.GPIO
2. time
3. socket
4. pyautogui

## Dependecies Installation
To install PyAutoGUI, install the pyautogui package from PyPI and dependencies.

On Windows, this is:

    C:\Python34\pip.exe install pyautogui

On OS X, this is:

    pip3 install pyobjc-core

    pip3 install pyobjc

    pip3 install pyautogui

If you are running El Capitan and have problems installing pyobjc try:

    MACOSX_DEPLOYMENT_TARGET=10.11 pip install pyobjc

On Linux, this is:

    pip3 install python3-xlib

    sudo apt-get install scrot

    sudo apt-get install python3-tk

    sudo apt-get install python3-dev

    pip3 install pyautogui

PyAutoGUI will try to install Pillow (for its screenshot capabilities). This happens when pip installs PyAutoGUI.
All other packages should come pre-installed with python. If not google is always there for rescue.

## To Execute
Connect your PC and Raspberry Pi to same network.
Execute Server.py on your PC and execute usds.py on Raspberry Client.

You are good to go.
The slides would be changed to next slide when your hand will be in a range of 20 cm from the ultrasonic sensor.
