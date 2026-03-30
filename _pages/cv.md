---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.Tech in Mechanics and Design, Indian Institute of Technology, Hyderabad, 2022–2025 — GPA: 9.47/10
* B.E in Mechanical Engineering, Anil Neerukonda Institute of Technology and Sciences (Andhra University), 2012–2016 — GPA: 8.32/10

Work experience
======
* **Application Developer — IBM India Pvt. Ltd., Bengaluru** (June 2016 – March 2020)
  * Enhanced and maintained enterprise financial management software built on Uniface 9.7
  * Integrated third-party SOAP-based web services into the application, reducing customer application processing time
  * Contributed to a major software upgrade from a legacy Uniface version to 9.7, enabling secure modern drivers for cross-platform connectivity
  * Developed SQL views and materialized views for data analysis and reporting
  * Collaborated with clients and cross-functional teams to define technical requirements for system enhancements
  * Supported onshore teams in diagnosing and resolving production issues
  * Authored documentation for system changes, enhancements, and bug fixes

* **Research Assistant — ASPIRE Lab, IIT Hyderabad** (2022 – 2025)
  * Conducted research under Prof. R. Prasanth Kumar in the areas of aerial robotics, swarm systems, and biped locomotion
  * Developed a four-quadcopter swarm system for collaborative payload transport — published at IEEE ICRM 2025 (**Best Paper Award**)
  * Contributed to experimental validation of a prismatic-knee underactuated biped robot for obstacle crossing — acknowledged in resulting publication

* **Motion Planning Engineer — Svaya Robotics Pvt. Ltd., Hyderabad** (July 2025 – Present)
  * Diagnosed and optimized motion planner execution timing, reducing latency to sub-1 ms and improving real-time determinism
  * Identified and resolved real-time timing bottlenecks through collaboration with the embedded systems team
  * Modeled motor friction characteristics to enhance torque-based collision detection accuracy in a dual-arm robotic system
  * Contributed to system architecture migration from a Finite State Machine (FSM) based planner to a Behavior Tree (BT) based framework, improving modularity of the codebase
  * Implemented sampling-based motion planners (RRT, RRT*, ABIT*) from scratch without MoveIt, directly integrated into the robot's planning stack
  * Annotated vision datasets using Roboflow to support training of perception models
  * Collaborated with the Computer Vision team to integrate perception outputs with the motion planning stack
  * Tested and validated new features and APIs to ensure system reliability and performance

Skills
======
* **Motion Planning:** RRT, RRT*, ABIT*, Behavior Trees, FSM, trajectory generation, collision detection
* **Robotics:** PX4 Autopilot, ROS, MoveIt, drone systems, swarm robotics, biped locomotion
* **Embedded Systems:** ESP32, Teensy 4.1, STM32, Raspberry Pi, real-time control, PWM, MQTT, RTK GNSS, nRF24, LoRa SX1278
* **Programming:** C++, Python, MATLAB
* **Tools:** Roboflow, ANSYS, Git, SQL

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  