---
title: "Custom Drone Flight Controller on Teensy 4.1"
excerpt: "Built a custom flight controller performing attitude stabilization using a Teensy 4.1 microcontroller and ICM-20948 IMU."
collection: portfolio
---

## Overview

An experimental drone flight controller built from scratch performing **attitude stabilization**. Rather than relying on existing autopilot firmware, this project involved writing custom flight controller code on bare hardware — covering IMU interfacing, sensor calibration, RC input decoding, and motor control.

## Hardware

- **Teensy 4.1** — high-performance ARM Cortex-M7 microcontroller (600 MHz)
- **ICM-20948** — 9-axis IMU (accelerometer, gyroscope, magnetometer)
- **FlySky iA10B** — 10-channel RC receiver
- **SimonK ESCs** — motor speed controllers

## Circuit Diagrams

<img src="https://github.com/user-attachments/assets/1cfff998-10d5-4b12-9ecb-49a24050f692" alt="Circuit diagram 1" style="max-width:100%;"/>
<img src="https://github.com/user-attachments/assets/c932e833-69af-4e07-b393-bf3ae24dd56b" alt="Circuit diagram 2" style="max-width:100%;"/>

## Testing Video

<video width="100%" controls>
  <source src="https://github.com/user-attachments/assets/4380e5ea-ffb0-4b9b-933b-dabfe181ca2c" type="video/mp4">
  Your browser does not support the video tag.
</video>

## Implementation

- Firmware written in **C++ (Arduino framework)** on the Teensy 4.1
- IMU data processing with **level calibration, gyroscope calibration, and accelerometer calibration** for accurate attitude estimation
- RC input decoding from FlySky receiver for manual control
- PWM output to SimonK ESCs for motor control

## Links

- [Source Code (GitHub)](https://github.com/shyamsridhar/Teensy-Drone)
