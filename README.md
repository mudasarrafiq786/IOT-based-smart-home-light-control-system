# README: IoT-based Smart Home Light Control System

## Project Overview
This project is an IoT-based Smart Home Light Control System designed to automate and manually control home lighting. The system uses sensors and actuators to adjust lighting based on environmental conditions and allows remote control via a mobile app.

---

## Features
- **Automatic Control**:
  - Turns the light on when the room is dark (using an LDR sensor).
  - Activates the light when motion is detected (using a PIR sensor).
  - Turns the light off after a specified period of inactivity.
- **Manual Control**:
  - Allows users to control the light via a mobile app (Blynk or ThingSpeak).
- **Cloud Monitoring**:
  - Provides real-time updates on sensor data and light status through the cloud platform.

---

## System Components
### Hardware
1. **ESP32**: Microcontroller for processing sensor data and controlling actuators.
2. **LDR Sensor**: Measures ambient light intensity.
3. **PIR Sensor**: Detects motion in the room.
4. **Relay Module**: Switches the light on/off.
5. **LED Light**: Simulates the home lighting.

### Software
1. **Arduino IDE**: Used for programming the ESP32.
2. **Cloud Platform**:
   - Blynk or ThingSpeak for remote control and monitoring.

---

## Installation and Setup

### Hardware Connections
1. Connect the LDR sensor to the ESP32 to measure ambient light intensity.
2. Connect the PIR sensor to the ESP32 to detect motion.
3. Connect the relay module to the ESP32 to control the LED light.
4. Attach an LED light or small light bulb to the relay module.

### Software Configuration
1. Install the Arduino IDE on your computer.
2. Install the necessary libraries for ESP32 and the chosen cloud platform (Blynk/ThingSpeak).
3. Write and upload the code to the ESP32 using the Arduino IDE.

### Cloud Integration
1. Create an account on Blynk or ThingSpeak.
2. Configure the mobile app/dashboard to monitor sensor data and control the light.

---

## Usage Instructions
1. **Automatic Mode**:
   - Place the LDR sensor in a location where it can detect ambient light.
   - Ensure the PIR sensor is positioned to detect motion in the room.
   - The system will automatically control the light based on light levels and motion.

2. **Manual Mode**:
   - Open the mobile app (Blynk/ThingSpeak).
   - Use the app to toggle the light on/off as needed.

---

## Testing and Optimization
1. Test the LDR sensor to ensure the light turns on/off based on the ambient light threshold.
2. Verify the PIR sensor activates the light when motion is detected and deactivates it after inactivity.
3. Test the manual control functionality via the mobile app.
4. Optimize sensor placement for accurate detection.

---

## Technologies Used
- **ESP32**: For IoT connectivity and processing.
- **LDR and PIR Sensors**: For light and motion detection.
- **Relay Module**: For switching the light on/off.
- **Blynk/ThingSpeak**: For remote monitoring and control.
- **Arduino IDE**: For programming the ESP32.

---

## Conclusion
The IoT-based Smart Home Light Control System is a practical, user-friendly solution for automating home lighting. It combines the convenience of automatic adjustments with the flexibility of manual control, making it a valuable addition to any smart home setup.

