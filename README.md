# ESP8266-Ubidots-ECG-Sensor
This repository contains the code for an ESP8266-based ECG sensor that communicates with the Ubidots cloud platform. The sensor reads ECG data and publishes it to Ubidots via MQTT for real-time monitoring.

# ESP8266 Ubidots ECG Sensor

## Introduction

This repository features the code for an ESP8266-based ECG sensor that seamlessly integrates with the Ubidots cloud platform. The sensor reads ECG data and transmits it to Ubidots using MQTT, enabling real-time monitoring and analysis.

## Hardware Setup

- ESP8266 board
- ECG Sensor (connected to A0 pin)
- [Other hardware details...]

## Software Dependencies

- ESP8266WiFi library
- PubSubClient library
- [Other dependencies...]

## Configuration

1. Set your WiFi credentials:
   
   #define WIFISSID "YourWiFiSSID"
   #define PASSWORD "YourWiFiPassword"
2. Obtain your Ubidots token and set it:

#define TOKEN "YourUbidotsToken"
3. Customize MQTT client name:


#define MQTT_CLIENT_NAME "YourECGSensor"
4. Configure Ubidots and device labels:

#define VARIABLE_LABEL "myecg"
#define DEVICE_LABEL "esp8266"
# How to Run
Clone this repository.
Open the Arduino IDE.
Install necessary libraries.
Configure the code with your credentials.
Upload the code to your ESP8266 board.
Monitor the serial console for connection status.

# Ubidots Configuration
Create a Ubidots account: Ubidots Sign Up
Obtain your Ubidots token and set up variables.
