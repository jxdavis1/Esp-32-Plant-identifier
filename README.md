# ESP32-CAM Project

## Project Goal
This project demonstrates how to set up an ESP32-CAM module for real-time video streaming and image capture, showcasing its capabilities for DIY surveillance systems.

## Software and Hardware Requirements
| Component        | Description                                | Version/Details         |
|-------------------|--------------------------------------------|--------------------------|
| ESP32-CAM         | Wi-Fi-enabled camera module               | AI-Thinker Model         |
| FTDI Programmer   | USB-to-Serial Adapter                     | 5V-compatible            |
| Arduino IDE       | Development environment                   | 2.0.0 or higher          |
| Libraries         | `ESP32`, `WiFi`, `esp_camera`             | Latest stable release    |
| Power Supply      | Micro-USB or External Power (5V/2A)       |                         |
| Jumper Wires      | For wiring connections                    |                         |

**Hidden Details:**
- Ensure the ESP32-CAM is properly connected to the FTDI programmer.
- Select the correct COM port in Arduino IDE.
- Use a reliable microSD card for storage, formatted to FAT32.

## Wiring Diagram
[Include an image or PDF of the wiring diagram here, created in Tinkercad or Google Docs.]

## How to Run the Project
1. Install Arduino IDE and necessary libraries.
2. Connect the ESP32-CAM to the FTDI programmer.
3. Upload the sketch from the `src` folder.
4. Power the ESP32-CAM and access the stream via the IP address displayed on the serial monitor.

## License
This project is licensed under the [MIT License](LICENSE).
