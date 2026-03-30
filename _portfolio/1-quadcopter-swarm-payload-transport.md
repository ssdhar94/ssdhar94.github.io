---
title: "Collaborative Payload Transport Using a Four-Quadcopter Swarm"
excerpt: "Designed and validated an outdoor multi-drone swarm system for coordinated payload transport using PX4, RTK GNSS, and MQTT over Wi-Fi mesh."
collection: portfolio
---

## Overview

This project was developed as part of my Master's thesis at IIT Hyderabad and resulted in a published paper at the **2025 International Conference on Robotics and Mechatronics (ICRM), IEEE**, where it received the **Best Paper Award**.

The system demonstrates collaborative payload transport using a swarm of four quadcopters in an outdoor environment, validated with a real 1 kg payload.

## System Architecture

A **leader-follower architecture** was used:
- The **leader drone** receives the mission and broadcasts commands to follower drones
- **Follower drones** autonomously execute commands while maintaining formation
- Communication between drones uses **MQTT over a Wi-Fi mesh network**

## Key Technologies

- **PX4 Autopilot** — flight controller firmware on all four drones
- **Raspberry Pi Zero 2 W** — onboard compute for communication and control logic
- **RTK GNSS** — centimeter-level outdoor positioning, with correction data (RTCM) routed via cloud infrastructure
- **MQTT** — lightweight publish-subscribe messaging for inter-drone coordination
- **WebSocket server** — ground station interface for mission control
- **C++ / Python** — onboard software for sender/receiver communication and RTCM data handling

## Hardware

**Leader Quadcopter**

<img src="https://github.com/user-attachments/assets/535e3ecd-2891-4526-9cf7-c5e469ce856e" alt="Leader quadcopter hardware diagram 1" style="max-width:100%;"/>
<img src="https://github.com/user-attachments/assets/6d47b237-65a5-4795-8861-0551d512694e" alt="Leader quadcopter hardware diagram 2" style="max-width:100%;"/>

**Follower Quadcopters**

<img src="https://github.com/user-attachments/assets/8feff6b7-11d5-41c4-a878-c614737b9151" alt="Follower quadcopter hardware diagram 1" style="max-width:100%;"/>
<img src="https://github.com/user-attachments/assets/58f654f6-5c60-4918-99ee-91c6fe8dc42a" alt="Follower quadcopter hardware diagram 2" style="max-width:100%;"/>

## Demo Video

<video width="100%" controls>
  <source src="https://github.com/user-attachments/assets/9830d044-755f-4c61-a4e7-538bba5bb543" type="video/mp4">
  Your browser does not support the video tag.
</video>

## Results

- Successfully transported a **1 kg payload** outdoors
- Maintained **formation stability** during ascent, lateral maneuvers at up to **20 km/h**, and descent
- Demonstrated reliable RTK-based positioning with cloud-routed corrections

## Links

- [Published Paper (IEEE Xplore)](https://ieeexplore.ieee.org/abstract/document/11349069/)
- [Source Code (GitHub)](https://github.com/ssdhar94/ProjectBkp/tree/main)
