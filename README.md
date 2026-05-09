IoT Light Control via Mobile App

Overview
This project is an IoT-based Light Control System that allows users to control home lights using a mobile application through the internet or Wi-Fi. The system uses a microcontroller like ESP8266/NodeMCU connected to a relay module to switch lights ON and OFF remotely. This project is useful for smart home automation and energy-saving applications.

Features
Control lights using a mobile app
Wireless communication through Wi-Fi
Remote ON/OFF switching
Simple and low-cost home automation project
Real-time control from anywhere
Beginner-friendly IoT project

Components Required
NodeMCU ESP8266 / ESP32
Relay Module
Bulb with Holder
Jumper Wires
Breadboard
Mobile Phone
Wi-Fi Connection
Power Supply

Software Used
Arduino IDE
Blynk App / IoT Mobile App
ESP8266 Board Package
Blynk Library

Working Principle
The NodeMCU connects to the Wi-Fi network and communicates with the mobile application. When the user presses the ON/OFF button in the app, a signal is sent to the NodeMCU. The microcontroller then controls the relay module to switch the connected light ON or OFF.

Circuit Connections
Component
NodeMCU Connection
Relay IN
D1
Relay VCC
3.3V / 5V
Relay GND
GND

Mobile App Setup
Install the Blynk app from Play Store or App Store.
Create a new project in the app.
Select NodeMCU ESP8266 as the device.
Copy the Authentication Token.
Add a button widget for light control.
Set the button pin to D1.

Arduino IDE Setup
Open Arduino IDE.
Install ESP8266 board package.
Install Blynk library from Library Manager.
Select NodeMCU board.
Upload the program to NodeMCU.

Output
Light can be controlled from the mobile app.
Real-time ON/OFF operation through Wi-Fi.
Remote access to home appliances.
