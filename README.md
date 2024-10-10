# Self-Healing Mesh Network Node With Dynamic Routing

## Software for this project is still under development

This repository contains the design and implementation files for a PCB that serves as a node in a self-healing mesh network, developed as part of my thesis project. The board incorporates 2.4GHz WiFi, Bluetooth, and an array of environmental sensors,a power management system, and is designed for battery-powered operation.

![Screenshot of a 3d render of the board](https://github.com/lyraei/ion_board/blob/main/documentation/board3d_view.png)

## Features

* **Mesh Networking:** Designed for integration into a dynamic routing, self-healing mesh network. (Further details on the mesh networking protocol will come.)
* **Wireless Connectivity:**  Integrated 2.4GHz WiFi and Bluetooth for communication and data transmission.
* **Environmental Sensing:**
    * BME280: Temperature, humidity, and barometric pressure sensing.
    * ZMOD4410: Air quality sensor with embedded artificial intelligence.
    * APDS-9250: Digital ambient light sensor (RGB and IR).
* **Power Management:**
    * BQ24073: Linear battery charger with power path for seamless operation during charging.
    * TPS62842DGRR: High-efficiency step-down switching converter.
* **Battery Powered:** Designed for low-power operation and extended battery life.

## Repository Contents

* `/hardware`: Contains the PCB design files.
* `/firmware`: Will contain the firmware source code.
* `/documentation`: Contains additional documentation, BOM and schematics.

## Hardware

* **Microcontroller:** ESP32-C6FH4
* **PCB Size:** 41.15 mm* 55.95 mm
* **Layers:** 4

## Software

* **Operating System:** TBD 
* **Mesh Networking Protocol:** TBD
* **Libraries Used:** TBD

**Contact:**

Szymon Urban - urbanszymon13@gmail.com
