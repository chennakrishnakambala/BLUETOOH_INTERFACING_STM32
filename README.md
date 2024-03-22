STM32G431RB Bluetooth Control


This repository contains code and documentation for interfacing Bluetooth with the STM32G431RB microcontroller using the HC-05 Bluetooth module. The project demonstrates how to control a fan and light using relay modules via a mobile application. The development was done using STM32CubeIDE.

Features:


Bluetooth Interfacing: Establishes a connection between the STM32G431RB microcontroller and a mobile device using the HC-05 Bluetooth module.

Relay Control: Demonstrates how to control a fan and light using relay modules connected to the STM32G431RB microcontroller.

Hardware Requirements:

STM32G431RB microcontroller board
HC-05 Bluetooth module
Relay modules for fan and light control
Mobile device with Bluetooth capability



Usage:

Connect the HC-05 Bluetooth module to the STM32G431RB microcontroller as per the provided schematic.

Upload the provided Arduino code (main.cpp) to the STM32G431RB microcontroller using STM32CubeIDE.

Install a Bluetooth terminal application on your mobile device (e.g., Bluetooth Terminal HC-05).

Pair your mobile device with the HC-05 Bluetooth module.

Use the mobile application to send commands to the STM32G431RB microcontroller and control the fan and light via relay modules.
