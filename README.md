# Gemini-Flight-Computer

The Gemini Rev.1 TVC flight computer is an advanced board designed for avionics and telemetry in rocketry, featuring an Arduino Nano microcontroller for processing and executing a PID control algorithm. It integrates key sensors like the BMP388 for pressure readings and the MPU-6050 IMU for gyro and acceleration data across three axes. The system includes a piezo buzzer and RGB LED for status indication, an NRF24L01 module for telemetry communication, and outputs for pitch and yaw servo motors in the thrust vector control (TVC) gimbal, all powered by a 9V battery.

Future enhancements to the Gemini Rev.1 include upgrading to a more powerful microcontroller for increased capability, such as the Teensy 4.1 board.  Furthermore, implementing a data logger with an SD card for reading telemetry data and storing for later use may help improve board reliability. Adding sensors like a magnetometer and a secondary communication module for redundancy would also be a consideration, while incorporating an adaptive PID control algorithm using AI could enhance flight stability. Additionally, expanding status feedback options and including safety features, such as fail-safes and automatic recovery modes, would further increase reliability and performance for various mission profiles.

Theory

![alt text](https://www.apogeerockets.com/images/newsletter/Newsletter-515-Images/Newsletter-515-Figure-1-Lg.jpg)
