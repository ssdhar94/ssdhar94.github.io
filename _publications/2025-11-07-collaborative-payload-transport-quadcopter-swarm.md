---
title: "Collaborative Payload Transport Using a Four-Quadcopter Swarm with RTK and MQTT-Based Coordination"
collection: publications
category: conferences
permalink: /publication/2025-11-07-collaborative-payload-transport-quadcopter-swarm
excerpt: 'Design and experimental validation of a collaborative payload transport system using a swarm of four quadcopters, employing a leader-follower architecture with MQTT-based coordination and RTK GNSS for high-precision outdoor positioning.'
date: 2025-11-07
venue: '2025 International Conference on Robotics and Mechatronics (ICRM) — Best Paper Award'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/11349069/'
citation: 'Neeli Shyam Sridhar, Aashish Sahu, Sarimella Rami Reddy, R Prasanth Kumar. (2025). &quot;Collaborative Payload Transport Using a Four-Quadcopter Swarm with RTK and MQTT-Based Coordination.&quot; <i>2025 International Conference on Robotics and Mechatronics (ICRM)</i>. pp. 1–6. IEEE.'
---

This paper presents the design and experimental validation of a collaborative payload transport system using a swarm of four quadcopters in an outdoor environment.

**Key contributions:**
- Leader-follower swarm architecture with mission commands distributed via **MQTT over Wi-Fi mesh**
- **RTK GNSS** positioning for centimeter-level accuracy, with correction data routed through cloud infrastructure
- Each quadcopter runs **PX4 Autopilot** with a Raspberry Pi Zero 2 W for onboard compute and communication
- Successfully transported a **1 kg payload** while maintaining formation stability during ascent, maneuvers, and descent
