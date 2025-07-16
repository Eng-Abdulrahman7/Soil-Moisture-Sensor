# Soil-Moisture-Sensor
This project is a soil moisture monitoring system built with Arduino.

 It uses a **Soil Moisture Sensor to measure the moisture level in the soil and control an LED based on the moisture level. The system also includes a Slide Switch to toggle the functionality of the system (turning it on and off).

## Features
- Soil Moisture Sensor: Measures the moisture level of the soil and provides an analog reading to determine how wet or dry the soil is.
- LED Indicator: An LED is turned on when the soil is dry and off when it is moist.
- Slide Switch: Allows the user to enable or disable the monitoring system.
- Analog and Digital Sensor Programming: The system can be configured to use both analog and digital outputs.

## Components Used
- Arduino Uno: Microcontroller to run the project.
- Soil Moisture Sensor: Analog sensor used to measure soil moisture.
- LED: Used to indicate the moisture level.
- Slide Switch: Used to control the activation of the system.

## Circuit Diagram
The circuit includes:
- The Soil Moisture Sensor is connected to Arduino's **A0 pin for analog input.
- The LED is connected to Pin 13 on the Arduino.
- The Slide Switch is used to control the activation of the system and is connected to Pin 2.

## How it Works
1. The Slide Switch is used to turn the system on or off. When turned on, the system will start measuring the soil moisture.
2. The Soil Moisture Sensor will output a value that is read by the Arduino. If the moisture level is below a certain threshold (indicating dry soil), the LED will turn on.
3. If the moisture level is above the threshold (indicating wet soil), the LED will turn off.
4. The system will continue to monitor the soil moisture as long as the switch is on.

## Setup Instructions
1. Download the code from this repository and upload it to your Arduino.
2. Connect the components according to the circuit diagram.
3. Open the Serial Monitor to view the real-time moisture readings.
4. Use the Slide Switch to control the system.
