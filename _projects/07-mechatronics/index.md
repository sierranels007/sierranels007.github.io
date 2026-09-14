---
layout: post
title: Mechatronics Fundamentals
description: Built and tested Arduino based LED, DC motor, and stepper motor circuits to explore the connection between electronic controls and physical motion.
skills:
  - Arduino
  - Mechatronics
  - Circuit Prototyping
  - Breadboarding
  - LED Control
  - DC Motor Control
  - Stepper Motor Control
  - Motor Driver Integration
  - Electrical Troubleshooting
  - Functional Testing

main-image: /breadboard.jpeg
---

## Project Overview

These smaller builds helped me understand the connection between electronics, control logic, and physical hardware. I used an Arduino Mega, breadboards, LEDs, resistors, motor drivers, jumper wires, and external power supplies to build and test several mechatronic systems.

The projects progressed from controlling simple LED outputs to operating DC and stepper motors. They were not parts of one large system, but together they gave me practical experience with the fundamentals that make electromechanical systems work.

---

## LED Control and Circuit Prototyping

I began by wiring multiple LEDs to an Arduino Mega through a breadboard. Each LED was connected with a resistor to limit current and protect the component.

The Arduino was programmed to control the LEDs as individual outputs. This helped me become more comfortable with:

- Reading a basic circuit layout
- Using breadboard power and ground connections
- Selecting and placing current-limiting resistors
- Connecting components to digital output pins
- Uploading and testing Arduino programs
- Checking wiring when the physical output did not match the intended sequence

{% include image-gallery.html images="led-lights.jpeg" height="600" %}

*Arduino-controlled LED circuit assembled and tested on a breadboard.*

Even though the circuit was simple, it introduced an important mechatronics lesson: the program can be correct while the physical system is still wrong. Loose connections, incorrect pin placement, reversed LED polarity, or a missing ground can prevent the circuit from working as expected.

---

## DC Motor Control

The next build introduced motor control using an Arduino Mega, an external DC power supply, and a motor-driver module.

The motor driver acted as the interface between the Arduino and the DC motor. The Arduino provided the low-power control signals, while the external power supply provided the electrical power required to operate the motor.

{% include image-gallery.html images="motor.jpeg" height="600" %}

*DC motor test setup using an Arduino Mega, motor-driver module, breadboard, and programmable power supply.*

This setup helped me understand why a motor should not be powered directly from an Arduino output pin. Motors require more current than the microcontroller can safely provide and can introduce electrical loads that must be managed separately.

The test involved:

- Connecting the Arduino to the motor driver
- Supplying external power to the motor circuit
- Establishing a common electrical reference between components
- Sending control signals from the Arduino
- Testing the motor’s response
- Checking wiring and power connections during troubleshooting

---

## Stepper Motor Control

I also built a stepper motor control circuit using an Arduino Mega and a motor-driver module.

Unlike a basic DC motor, a stepper motor rotates through controlled increments. The driver energizes the motor windings in a sequence, allowing the Arduino to control the motor’s movement more deliberately.

{% include image-gallery.html images="steppa.jpeg" height="600" %}

*Stepper motor connected to an Arduino Mega and motor driver during bench testing.*

This build required coordination between:

- Arduino output signals
- Motor driver input connections
- Stepper motor wiring
- External power
- Command sequence and timing
- Mechanical response of the motor shaft

The circuit gave me a better understanding of how digital commands become physical rotation. It also showed why wiring order and signal sequencing matter—a motor can be fully connected and still behave incorrectly if the phases are connected in the wrong order.

---

## Testing and Troubleshooting

These projects involved a lot of checking, rewiring, and trying again. When a circuit did not work as intended, I worked through the system by checking:

- Power and ground connections
- Jumper wire placement
- Arduino pin assignments
- Component polarity
- Motor driver connections
- External supply settings
- Whether the code and physical wiring matched
- The response of the LED or motor after each change

Testing one part of the system at a time made it easier to isolate problems instead of changing everything at once.

---

## Engineering Takeaways

These builds gave me a practical introduction to mechatronics and helped connect programming with something I enjoy more: seeing a physical system move and respond.

The biggest takeaway was that mechanical, electrical, and control components cannot be treated as separate worlds. A motor may be mechanically capable of producing motion, but it still needs the correct power, wiring, driver, and commands to do anything useful.

I would not call myself an electrical engineer after a few breadboards, but I am comfortable assembling basic Arduino circuits, integrating motor drivers, testing electromechanical components, and working through the system when nothing moves on the first try.
