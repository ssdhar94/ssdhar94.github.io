---
title: "Prismatic Biped Robot — Obstacle Crossing Locomotion"
excerpt: "Contributed to experimental validation of a prismatic-knee underactuated biped robot for obstacle-crossing locomotion, with contributions acknowledged in the resulting publication."
collection: portfolio
---

## Overview

Contributed to the experimental validation of a **prismatic-knee underactuated biped robot** capable of crossing obstacles. The work covered embedded software development, actuator characterization, and mechanical design refinement. Contributions are acknowledged in the resulting peer-reviewed publication.

**Published paper:** [Obstacle crossing in revolute and prismatic knee underactuated biped robots](https://doi.org/10.1016/j.robot.2026.105340) — *Robotics and Autonomous Systems*, Vol. 198, p. 105340, Elsevier, April 2026.

## Contributions

- Experimental validation of the prismatic biped robot for obstacle-crossing locomotion
- Servo torque characterization and actuator capability validation for locomotion experiments
- Iterative mechanical design refinement of the experimental robot platform
- Developed embedded software on **ESP32** for actuator control
- Extended low-level motor control libraries (ST3215) to support experimental requirements — including converting prismatic motors to PWM mode and enabling continuous stepper rotation
- Supported locomotion performance validation of the prismatic knee configuration

## Experimental Demonstration

![Prismatic biped obstacle crossing](https://raw.githubusercontent.com/ssdhar94/prismatic_biped_codes/main/output.gif)

<video width="100%" controls>
  <source src="https://raw.githubusercontent.com/ssdhar94/prismatic_biped_codes/main/thin_1_5x_720p30.m4v" type="video/mp4">
  Your browser does not support the video tag.
</video>

## Tech Stack

- **ESP32** — embedded control
- **ST3215 servo motors** — custom library extension for stepper mode and PWM mode
- **C++** — firmware development

## Links

- [Source Code (GitHub)](https://github.com/ssdhar94/prismatic_biped_codes)
- [ST3215 Updated Library (GitHub)](https://github.com/ssdhar94/ST3215_library)
- [Published Paper](https://doi.org/10.1016/j.robot.2026.105340)
