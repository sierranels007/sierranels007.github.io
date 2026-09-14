---
layout: post
title: Automated Can Crusher
description: Collaborated on the design and construction of a functional automated can crusher integrating mechanical components, CAD-designed parts, a motor-driven crushing mechanism, sensors, Arduino control, and prototype testing.
skills:
  - Mechanical Design
  - SolidWorks
  - Mechatronics
  - Arduino
  - Stepper Motor Control
  - Sensor Integration
  - FDM Additive Manufacturing
  - Prototype Assembly
  - System Testing
  - Troubleshooting
main-image: /can-crusher.jpeg
---

## Project Context

This team project challenged us to design and build a functional system capable of positioning and crushing an aluminum can automatically.

The project required more than creating a crushing force. We also had to consider can placement, actuator alignment, structural support, motor control, sensor feedback, user interaction, and the sequence of the complete system.

---

## My Contribution

I contributed to the mechanical design, CAD development, fabrication, assembly, and testing of the prototype.

My work included:

- Designing mechanical components in SolidWorks
- Supporting the design of the can holder and crushing plate
- Developing mounting and actuator-support geometry
- Producing the actuator housing using FDM additive manufacturing
- Assisting with Arduino, motor, button, and sensor integration
- Evaluating the alignment between the actuator, crushing plate, and can
- Participating in system assembly and functional testing
- Troubleshooting mechanical and electrical integration issues

Because this was a team project, the final prototype combined our individual mechanical, electrical, and programming contributions.

---

## Mechanical Design

The crushing mechanism had to transfer force through the center of the can while remaining aligned throughout its motion.

The mechanical design included:

- A vertical crushing plate
- A holder to maintain the can’s position
- An actuator and motor-support structure
- A rigid enclosure
- A front access door
- CAD-designed and additively manufactured components

{% include image-gallery.html images="actuator-housing.jpeg" height="550" %}

*FDM-printed actuator housing used to support the motor-driven mechanism and maintain alignment during operation.*

The position of the crushing plate and can holder was evaluated to reduce off-center loading. Misalignment could cause the can to tilt, buckle unpredictably, or interfere with the enclosure instead of compressing cleanly.

---

## System Integration

The mechanical assembly was integrated with an Arduino-based control system, stepper-motor components, user inputs, sensors, and a display.

The control sequence allowed the system to:

1. Detect or receive a user command
2. Position the crushing mechanism
3. Apply the crushing motion
4. Stop or reverse the mechanism
5. Communicate system status to the user

This stage required us to treat the crusher as one connected system. A mechanical component could work correctly by itself but still create problems if its position, travel, or timing did not match the electronics and control sequence.

---

## Prototype Testing

We tested the mechanism through repeated operating cycles while monitoring motion, alignment, sensor behavior, and system response.

<video controls playsinline preload="metadata" style="width: 100%; max-width: 850px; border-radius: 6px;">
  <source src="can-crusher-test.mp4" type="video/mp4">
  Your browser does not support embedded video.
</video>

*Prototype testing of the integrated crushing mechanism and control system.*

Testing helped us identify mechanical interference, positioning issues, and integration problems that were not obvious during CAD development.

---

## Functional Result

The completed prototype successfully applied enough force and controlled motion to crush an aluminum can.

{% include image-gallery.html images="crushed-can.jpeg" height="550" %}

*Aluminum can positioned beneath the crushing plate during functional testing.*

---

## Engineering Takeaways

This project showed me how quickly a design becomes more complicated when mechanical hardware, electronics, controls, and user interaction have to work together.

The biggest lesson was that successful integration depends on checking the relationships between components—not just designing each part independently. Actuator travel, structural support, can position, sensor placement, and control timing all had to make sense as one system.

It strengthened my ability to work through an imperfect prototype, diagnose problems across multiple engineering areas, and keep refining the design until the system performed its intended function.
