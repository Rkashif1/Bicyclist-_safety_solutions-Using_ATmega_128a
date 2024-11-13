# Bicyclists' Safety Solutions- Relative Positioning and Warning of Impending Vehicles Using Atmega 128a

This project presents a **Safety Device for Cyclists** designed to enhance rider safety by monitoring surrounding vehicles and alerting the cyclist of potential hazards. Using an accelerometer for relative positioning and an ultrasonic sensor to detect approaching vehicles, this device provides real-time alerts through a visual display and an audible buzzer.

## Project Overview

Bicyclist safety is critical, especially when it comes to collisions involving motor vehicles. This device aims to improve safety by tracking vehicles approaching from behind and providing position feedback in real-time. When a vehicle comes within a defined proximity, an audible alert is triggered, allowing the cyclist to respond and maintain a safe distance.

## Features

- **Position Tracking with Accelerometer:** The accelerometer tracks the cyclist’s coordinates on the X, Y, and Z axes and displays the data on a 16x2 LCD screen.
- **Proximity Warning System:** An ultrasonic sensor detects vehicles approaching from behind. When within a certain range, a piezo buzzer sounds an alert to warn the cyclist.
- **Real-Time Display:** Coordinates and distance alerts are shown on an LCD, allowing the cyclist to monitor their position and proximity to vehicles.

## Hardware Components

- **Atmega128A Microcontroller:** The core controller for processing sensor data and managing outputs.
- **ADXL335 Accelerometer:** Measures acceleration in X, Y, and Z axes to provide position feedback.
- **HC-SR04 Ultrasonic Sensor:** Detects the proximity of approaching vehicles to provide collision alerts.
- **Piezo Buzzer:** Emits an audible warning when a vehicle is too close, ensuring the cyclist’s awareness.
- **16x2 LCD Display:** Shows real-time position and warning information for easy monitoring.

## Setup and Usage

1. **Hardware Assembly:** Connect the accelerometer, ultrasonic sensor, LCD display, and piezo buzzer to the Atmega128A microcontroller.
2. **Code Upload:** Flash the provided C code onto the microcontroller using Microchip Studio.
3. **Testing:** Test the sensor responses by simulating vehicle proximity and observing the displayed position data and buzzer alerts.
4. **Deployment:** Attach the device to a bicycle for real-world testing and ensure proper operation during rides.

## Future Enhancements

- Integrate GPS for accurate location tracking.
- Implement additional safety alerts for side-approaching vehicles.
- Develop a mobile app to display data and alerts on a smartphone.

## Team Collaboration

This project was a collaborative effort, with team members working on various aspects:
- **Kashif & Ammar:** Interfacing the accelerometer and LCD with the Atmega128A for position tracking.
- **Raihan:** Configuring the ultrasonic sensor and piezo buzzer for proximity alerts.

## Conclusion

The Sensor-Based Safety Device for Cyclists provides essential safety features by monitoring and alerting cyclists of approaching vehicles. This device aims to reduce the risk of accidents, making cycling safer and more enjoyable.
