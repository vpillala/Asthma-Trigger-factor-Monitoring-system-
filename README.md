# IoT Asthma Trigger Monitoring System

## Overview

This repository contains the code and design files for an IoT-based perpetual monitoring system for asthma trigger factors. The system has been upgraded with the integration of an SPO2 (MAX30105) sensor, enhancing its capabilities for monitoring respiratory health. The project aims to improve the efficiency of both outdoor and indoor monitoring by 45%.

## Features

- **SPO2 Sensor Integration:** The system now includes an SPO2 sensor (MAX30105) to monitor blood oxygen levels, providing additional insights into respiratory health.
- **Enhanced Efficiency:** The monitoring efficiency has been improved by 45% for both outdoor and indoor environments.
- **Online Monitoring:** Utilizes the ESP8266 for real-time online monitoring, enabling remote access to health data.
- **Cloud Platform Integration:** The monitored values are presented on a cloud platform for easy access and analysis.

## Hardware Setup

- **SPO2 Sensor (MAX30105):** The sensor is integrated into the system to measure blood oxygen levels and enhance respiratory health monitoring.
- **ESP8266:** Used for online monitoring, enabling data access from anywhere.
- **PCB Board Design:** Prepared a PCB board design using KiCad for a compact and efficient hardware implementation.

## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/asthma-monitoring-system.git
    cd asthma-monitoring-system
    ```

2. Review the hardware setup and connection details in the `hardware_setup.md` file.

3. Upload the provided code to your ESP8266 board.

4. Set up the cloud platform for data presentation and analysis (details in `cloud_setup.md`).

5. Power on the system and monitor asthma trigger factors seamlessly.

## Software Requirements

- Arduino IDE for uploading code to ESP8266.
- Cloud platform account for data presentation (e.g., AWS, Azure, Google Cloud).

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code and design files.

## Acknowledgments

- Thanks to [SPO2 Sensor Library](link-to-library) for their contribution.
- Special mention to [KiCad](https://www.kicad.org/) for enabling efficient PCB board design.

