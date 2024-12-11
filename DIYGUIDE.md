DIY Guide for ESP32-CAM Project

This guide will walk you through the steps to set up and demonstrate the ESP32-CAM project. By the end, you’ll have a working system capable of real-time video streaming and image capture.

Required Components
Hardware
Component
Description
Quantity
ESP32-CAM Module
Wi-Fi-enabled camera module
1
Micro-USB Cable
For powering ESP32-CAM
1
Laptop
Laptop with USB ports
1

Software
Arduino IDE: Version 2.0.0 or higher
Libraries:
ESP32
WiFi
esp_camera

Step-by-Step Instructions
1. Set Up the Hardware
Connect ESP32-CAM to Laptop using USB:
Power the FTDI Programmer:
Use a micro-USB cable to connect the programmer to your computer.
2. Prepare the Software Environment
Install Arduino IDE:
Download and install the Arduino IDE from https://www.arduino.cc.
Install ESP32 Board Package:
Go to File > Preferences and add the following URL to the "Additional Boards Manager URLs":
https://dl.espressif.com/dl/package_esp32_index.json
Open Tools > Board > Boards Manager, search for "ESP32," and install the package.
Install Required Libraries:
Open Tools > Manage Libraries and install the WiFi and esp_camera libraries.
3. Create Sketch
Download or Write the Sketch:
Use the provided code in the repository or utilize edge impulse to assist in making the code for the AI model.
Train Model:
If utilizing Edge Impulse you will need to gather data and label the data to feed the model.
Build & Export Model:
Build model for arduino library
In Arduino IDE click include zip library file and select the build created from edge impulse
Select the Board and Port:
Go to Tools > Board > ESP32 Arduino > AI-Thinker ESP32-CAM.
Select the correct COM port under Tools > Port.
Generating Sketch
Use example sketch “ESP-32 camera” from library imported in from Edge Impulse.
Edit Sketch
Update code to reflect which ESP32-cam model you have.
Upload the Sketch:
Press the "Upload" button. 
4. Test the Setup
Open Serial Monitor

