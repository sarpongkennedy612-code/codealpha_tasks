# NorthNet

An offline, localized WiFi access point designed to deliver educational resources in zero-connectivity environments. Built for the CodeAlpha Internet of Things (IoT) Engineering internship.

## Overview
NorthNet utilizes an ESP32 microcontroller to broadcast an independent local network. When users connect via a mobile device or legacy computer, the microcontroller acts as a local web server, delivering HTML content directly from the chip without requiring active internet access. This project was developed as a lightweight infrastructure solution for basic school ICT labs.

## Tech Stack
* **Hardware Profile:** ESP32 Microcontroller (Simulated via Wokwi)
* **Firmware:** MicroPython
* **Protocols:** TCP/IP, HTTP, 802.11 b/g/n

## Execution
1. Open the [Wokwi ESP32 Simulator](https://wokwi.com/).
2. Select MicroPython as the environment.
3. Paste the `main.py` script into the editor.
4. Click **Play** to initialize the Access Point. 
5. The terminal will output `NorthNet Active!` alongside the local IP address serving the captive HTML payload.
6. <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d9b6da92-aaf5-4e0a-88db-184b0598156c" />
