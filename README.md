# carrycrop2x-mobile-app

## Introduction
This project involves an ESP32 microcontroller that reads sensor data through Modbus and transmits it via Bluetooth. The sensor data includes values such as moisture, temperature, conductivity, pH, nitrogen, phosphorus, and potassium. The data is serialized into JSON format and sent over Bluetooth. Additionally, the system can handle and log errors during data reading.

## Requirements
Ensure you have the following components and libraries:

 - ESP32 microcontroller
 - Arduino IDE with ESP32 board support
 - ArduinoJson library
 - BluetoothSerial library
 - ModbusMaster library

## Setup Instructions

 - **Install Arduino IDE:** Download and install the Arduino IDE from the official website.

 - **Add ESP32 Board Support:** In Arduino IDE, go to ```File > Preferences```. Add the following URL to the "Additional Board Manager URLs": ```https://dl.espressif.com/dl/package_esp32_index.json```. Then, go to ```Tools > Board > Board Manager```, search for ```esp32```, and install it.

 - **Install Required Libraries:** Go to ```Sketch > Include Library > Manage Libraries```, search for and install ```ArduinoJson```, ```BluetoothSerial```, and ```ModbusMaster``` libraries.

 - **Enable Bluetooth and SPP in ESP32:** Ensure that Bluetooth and Serial Port Profile (SPP) are enabled in the ESP32 configuration. If not, use the command ```make menuconfig``` to enable them.

## Description
The code in our project takes sensor data via Modbus, sets up Bluetooth on an ESP32, and sends it as a JSON object. The data is sent every 5 seconds.

## Our Product
<div align="center">
<img src = 'https://github.com/syedmohiuddinzia/carrycrop2x-mobile-app/assets/31742658/2621836e-eec1-4139-920b-e4ffb20d5b93' width=300 height=300>
</div>

## Contact

For the complete code, more detailed instructions and further assistance, feel free to reach out to the project owner via the contact information provided below:

Email: [syedmohiuddinzia@gmail.com](syedmohiuddinzia@gmail.com) 
