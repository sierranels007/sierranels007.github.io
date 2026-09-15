---
layout: post
title: Iron Man Arc Reactor CAD Recreation
description: Reverse-engineered a physical Iron Man arc reactor by disassembling it, measuring its components with digital calipers, documenting the geometry by hand, and rebuilding the complete multi-part assembly in SolidWorks.
skills:
  - Reverse Engineering
  - SolidWorks
  - Digital Caliper Measurement
  - Technical Sketching
  - Part Modeling
  - Assembly Modeling
  - Exploded Views
  - Engineering Drawings
  - Bill of Materials
main-image: /arc reactor.png
---

## Project Context

I completed this CAD recreation as the capstone project for my Mechanical Engineering Tools Laboratory course. The goal was to take an existing physical assembly, document its geometry, and recreate it as a complete SolidWorks assembly.

I chose an Iron Man arc reactor because it was a much better challenge than modeling a single solid part. Its layered construction, nested rings, repeated features, and large number of interconnected components required careful measurement and assembly planning.

My work focused on disassembling the physical reference, measuring and sketching its components, building the individual CAD models, and reconstructing the full assembly in SolidWorks. I did not manufacture or 3D print the physical reactor shown in the photographs.

---

## Measurement and Planning Process

I began by carefully disassembling the physical reactor so I could inspect each component individually. Instead of estimating the geometry from photographs, I used digital calipers to measure features such as:

- Outside and inside diameters
- Component thicknesses
- Hole sizes and locations
- Ring spacing
- Slot dimensions
- Support geometry
- Repeated angular features
- Interfaces between mating components

Before opening SolidWorks, I drew the individual parts by hand and recorded their important dimensions. This gave me a dimensional plan for each model and helped me identify which measurements controlled the assembly interfaces.

{% include image-gallery.html images="draw1.png, draw2.png, draw3.png, draw4.png" height="380" %}

*Selected hand sketches and caliper measurements completed before CAD modeling.*

---

## CAD Reconstruction

I modeled each component individually in SolidWorks using the measured geometry and my hand sketches as references.

The reactor required a mix of modeling techniques, including:

- Extruded and revolved features
- Circular patterns
- Repeated heat-sink and housing geometry
- Concentric rings
- Thin structural components
- Multi-body and multi-part organization
- Assembly mates and component positioning

Repeated features were created parametrically when possible. This made the design more organized and allowed related geometry to update consistently.

{% include image-gallery.html images="IMG_0048.jpeg, IMG_0049.jpeg" height="500" %}

*SolidWorks modeling and assembly development in progress.*

---

## Assembly Development

After creating the individual parts, I rebuilt the reactor as a SolidWorks assembly. The main challenge was maintaining the correct alignment and spacing across several concentric layers while positioning repeated components around the center axis.

Assembly mates were used to control:

- Concentric alignment
- Axial spacing
- Component orientation
- Repeated angular placement
- Connections between the reactor and display stand

Building the assembly revealed dimensional relationships that were not obvious while the parts were separated. When components did not align correctly, I returned to the original measurements and sketches to determine whether the part geometry or mate structure needed to be revised.

---

## Engineering Documentation

Once the assembly was complete, I produced an assembled drawing, exploded view, and bill of materials.

{% include image-gallery.html images="arc1.png, arc2.png" height="500" %}

*Assembled drawing and exploded view of the reconstructed reactor.*

{% include image-gallery.html images="arc3.png" height="550" %}

*Bill of materials documenting 23 component types used in the assembly.*

The exploded view communicates how the concentric rings, housing components, heat sinks, wire structures, and display stand fit together. The bill of materials provides a structured record of the component names and quantities.

---

## Result

The final result was a detailed SolidWorks reconstruction of the physical arc reactor, supported by original measurements, hand sketches, individual part models, a complete assembly, engineering drawings, an exploded view, and a bill of materials.

{% include image-gallery.html images="arcreact1.png" height="450" %}

*Physical arc reactor used as the recreation reference.*

---

## What I Learned

This project showed me that accurately recreating a physical assembly requires more than matching its appearance. I had to understand how the parts related, identify the dimensions controlling fit and placement, develop a logical modeling sequence, and compare the completed CAD assembly with the physical reference.

It also improved my confidence with large SolidWorks assemblies and taught me to use sketches, measurements, drawings, exploded views, and bills of materials as connected parts of one engineering workflow.
