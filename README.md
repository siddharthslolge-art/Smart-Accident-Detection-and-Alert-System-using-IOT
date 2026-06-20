# Smart-Accident-Detection-and-Alert-System-using-IOT 

## Overview

The Smart Accident Detection System is an IoT-based safety project that detects vehicle accidents using an ADXL345 accelerometer sensor. When an accident is detected, the system automatically sends SMS alerts, makes a phone call, and shares the accident location using GPS.

## Features

* Accident detection using ADXL345 accelerometer
* GPS location tracking
* SMS alert to emergency contacts
* Automatic emergency phone call
* Blynk mobile app notifications
* Manual SOS button for emergency situations

## Components Used

* ESP32
* ADXL345 Accelerometer
* NEO-6M GPS Module
* SIM800L GSM Module
* Buzzer
* Push Button (SOS)
* Blynk IoT Platform

## Working

1. The ADXL345 continuously monitors acceleration values.
2. If abnormal acceleration is detected, the system confirms the event.
3. The GPS module obtains the current location.
4. An SMS containing the accident location is sent to emergency contacts.
5. A phone call is made to the predefined emergency number.
6. Accident information is displayed in the Blynk application.

## Blynk Virtual Pins

| Virtual Pin | Function           |
| ----------- | ------------------ |
| V0          | Location           |
| V1          | Alert Status       |
| V2          | Acceleration Value |
| V3          | SOS Trigger        |
| V4          | Speed              |
| V5          | Time               |

## Future Improvements

* Machine learning for better accident detection
* Cloud data storage
* Integration with ambulance services
* Mobile application with live tracking

## Author

Siddharth Lolge

Computer Engineering Final Year Project
