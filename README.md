# Sensor Measurement Board

This project is an **open hardware measurement board** designed to read sensor data using an **ESP32 NodeMCU** and publish it via **MQTT**.

## 🧠 Description
The board allows you to measure environmental parameters using the following sensors:
- **BH1750** – Ambient light intensity (lux)
- **SHTC3** – Temperature and humidity
- **PIR Sensor** – Motion detection

The ESP32 NodeMCU reads all sensor values and publishes them through MQTT topics to any subscribed client or local broker.

## ⚙️ Features
- Integrated I²C bus for BH1750 and SHTC3
- Digital input for the PIR motion sensor
- ESP32 NodeMCU for data acquisition and MQTT publishing
- Open design suitable for educational or experimental use

## 🧩 Usage
You can flash your own firmware to the ESP32 to:
- Connect to your Wi-Fi network
- Publish data to a local or remote MQTT broker
- Integrate with home automation systems (e.g., Home Assistant)

## 🪪 License
This project is licensed under the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)**.

You are free to:
- Share — copy and redistribute the material in any medium or format  
- Adapt — remix, transform, and build upon the material  

Under the following terms:
- **Attribution** — You must give appropriate credit.  
- **NonCommercial** — You may not use the material for commercial purposes.  
- **ShareAlike** — You must distribute your contributions under the same license.  

🔗 License details: [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)  
SPDX-License-Identifier: CC-BY-NC-SA-4.0
