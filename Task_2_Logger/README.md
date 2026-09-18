# Logger

An offline hardware environment monitor designed to protect legacy lab equipment in zero-connectivity environments. Built for the CodeAlpha Internet of Things (IoT) Engineering internship.

## Overview
This system utilizes an ESP32 microcontroller paired with a DHT22 sensor to locally monitor room temperature and humidity. If temperatures exceed the safe operational threshold for the lab computers, the system triggers an immediate local alert, allowing for preventative measures without requiring internet telemetry.

## Tech Stack
* **Hardware Profile:** ESP32 Microcontroller, DHT22 Sensor (Simulated via Wokwi)
* **Firmware:** MicroPython
* **Logic:** Local threshold alerting

## Execution
1. Open the [Wokwi ESP32 Simulator](https://wokwi.com/).
2. Select the MicroPython Weather Logger template.
3. Paste the `main.py` script to override default MQTT logic with local threshold alerts.
4. Click **Play** and manipulate the physical DHT22 sensor slider.
5. The terminal outputs environmental metrics and triggers a critical warning when the temperature exceeds 30°C.
6. <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4d7ec38d-7743-435b-938a-a3099265209d" />
