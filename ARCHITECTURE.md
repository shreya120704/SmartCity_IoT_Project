# Overview / Architecture of the Solution

The architecture includes:

- A **Motion Detector (IoT4)** that senses motion.
- A **Microcontroller (MCU0)** receiving input from the motion sensor.
- A **Light (IoT3)** acting as the surveillance camera or lamp.
- A **Wireless Router (WRT300N)** named `HomeGateway` which connects all devices.
- All devices use the same SSID (`HomeGateway`) and obtain IPs via DHCP.

 When motion is detected:
- The MCU triggers the light (camera) to turn ON.

This simulates a simple smart surveillance system.
