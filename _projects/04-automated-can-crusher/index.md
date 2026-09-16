---
layout: post
title: Automated Can Crusher
description: Collaborated on the design and construction of a functional can crusher integrating mechanical components, CAD designed parts, a switch controlled actuator, Arduino control, additive manufacturing, and prototype testing.
skills:
  - Mechanical Design
  - SolidWorks
  - Mechatronics
  - Arduino
  - Stepper Motor Control
  - FDM Additive Manufacturing
  - Prototype Assembly
  - System Integration
  - Functional Testing
  - Troubleshooting

main-image: /can-crusher.jpeg
---

## Project Context

This team project challenged us to design and build an electromechanical system capable of crushing an aluminum can using a motor driven actuator.

Creating enough force was only one part of the challenge. We also had to consider can placement, actuator alignment, structural support, motor control, user operation, and how the mechanical and electrical components would function as one system.

---

## My Contribution

I contributed to the mechanical design, CAD development, fabrication, assembly, and testing of the prototype.

My work included:

- Designing mechanical components in SolidWorks
- Supporting the design of the can holder and crushing plate
- Developing mounting and actuator support geometry
- Producing the actuator housing using FDM additive manufacturing
- Assisting with Arduino, motor driver, and switch integration
- Evaluating the alignment between the actuator, crushing plate, and can
- Participating in system assembly and functional testing
- Troubleshooting mechanical and electrical integration issues

Because this was a team project, the final prototype combined our individual mechanical, electrical, and programming contributions.

---

## Mechanical Design

The crushing mechanism had to transfer force through the center of the can while remaining aligned throughout its vertical motion.

The mechanical design included:

- A vertical crushing plate
- A holder to maintain the can’s position
- An actuator and motor support structure
- A rigid enclosure
- A front access door
- CAD designed and additively manufactured components

{% include image-gallery.html images="actuator-housing.jpeg" height="550" %}

*FDM printed actuator housing used to support the motor driven mechanism and maintain its alignment during operation.*

The position of the crushing plate and can holder was evaluated to reduce off center loading. Misalignment could cause the can to tilt, buckle unpredictably, or interfere with the enclosure instead of compressing cleanly.

---

## System Integration

The mechanical assembly was integrated with an Arduino, stepper motor, motor driver, and user operated switch.

The switch controlled the direction of the actuator, allowing the crushing plate to move downward to compress the can and upward to return to its starting position.

The operating sequence was straightforward:

1. The user activated the switch
2. The Arduino sent a control signal to the motor driver
3. The stepper motor drove the actuator
4. The actuator moved the crushing plate up or down
5. The user released or reversed the switch to stop or change direction

The actuator did not automatically locate or position the crushing mechanism. Its movement was controlled directly by the user through the switch.

This kept the control system straightforward while still connecting the mechanical structure, electronics, motor, and actuator into one working prototype.

---

## Prototype Demonstration

The videos below show the assembled prototype during functional testing and demonstrate the actuator driven crushing motion.

<div style="display:flex; justify-content:center; align-items:flex-start; gap:1.5rem; flex-wrap:wrap; margin:1.5rem 0;">

  <iframe
    src="https://www.youtube.com/embed/8lSjFiVhfJM"
    title="Automated can crusher functional test 1"
    loading="lazy"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
    allowfullscreen
    style="width:100%; max-width:340px; aspect-ratio:9/16; height:auto; border:0; border-radius:12px;">
  </iframe>

  <iframe
    src="https://www.youtube.com/embed/oO_3jDdR3bo"
    title="Automated can crusher functional test 2"
    loading="lazy"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
    allowfullscreen
    style="width:100%; max-width:340px; aspect-ratio:9/16; height:auto; border:0; border-radius:12px;">
  </iframe>

</div>

*Functional testing of the switch controlled actuator and crushing mechanism.*

---

## Functional Result

The completed prototype successfully used the motor driven actuator to apply enough force to crush an aluminum can.

{% include image-gallery.html images="crushed-can.jpeg" height="550" %}

*Crushed aluminum can beneath the crushing plate following functional testing.*

The crushing plate traveled vertically through the enclosure while the can holder helped keep the can beneath the actuator. After compression, the switch could be reversed to raise the plate and reset the system.

---

## Engineering Takeaways

This project showed me how quickly a design becomes more complicated when mechanical hardware, electronics, controls, and user operation have to work together.

The biggest lesson was that successful integration depends on checking the relationships between components, not just designing each part independently. Actuator travel, structural support, crushing plate alignment, can placement, motor direction, and switch response all had to make sense as one system.

It strengthened my ability to work through an imperfect prototype, diagnose problems across multiple engineering areas, and refine the design until the system performed its intended function.
