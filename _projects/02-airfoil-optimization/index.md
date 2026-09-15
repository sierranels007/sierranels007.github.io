---
layout: post
title: Airfoil Structural Design Optimization
description: Developed a Python based optimization workflow to evaluate airfoil structural variables and identify a lightweight configuration with improved vibration performance.
skills:
  - Design Optimization
  - Python
  - NumPy
  - pymoo
  - Structural Analysis
  - Natural Frequency Evaluation
  - Eigenvalue Analysis
  - Technical Communication
main-image: /airfoil.jpeg
---

## Project Context

During the 2024 Office of Naval Research Pipeline Program at Penn State’s Applied Research Laboratory, I worked on a structural design optimization project focused on minimizing vibration in an airfoil inspired beam.

The challenge was to improve dynamic performance without treating mass, stiffness, geometry, and material selection as separate decisions. Each variable influenced the structural response of the complete system.

---

## Engineering Objective

The objective was to identify a combination of material and geometric properties that increased the structure’s natural frequency while maintaining a practical, lightweight design.

A structure operating near one of its natural frequencies can experience amplified vibration. By evaluating the relationship between mass and stiffness, the optimization process searched for designs that were less susceptible to resonance under operating conditions.

---

## My Role

I developed and evaluated the computational optimization workflow used for the project.

My work included:

- Defining material and geometric design variables
- Calculating structural mass and stiffness matrices
- Evaluating eigenvalues and natural frequencies
- Implementing a genetic algorithm workflow in Python
- Using NumPy for numerical calculations
- Using pymoo to manage the optimization process
- Comparing candidate designs based on performance
- Documenting and presenting the final results

---

## Computational Approach

For each candidate design, the program evaluated how the selected material properties and geometry affected the beam’s mass and stiffness.

The natural frequencies were determined from the structural eigenvalue relationship:

<div style="text-align: center; font-size: 1.35rem; margin: 1.5rem 0;">
  [K - &omega;<sup>2</sup>M]&phi; = 0
</div>

where:

- **K** is the stiffness matrix
- **M** is the mass matrix
- **&omega;** is the natural frequency
- **&phi;** is the corresponding mode shape

A genetic algorithm was used to explore multiple combinations of design variables. This allowed the program to search beyond a single manually selected design and compare candidate solutions using a consistent engineering objective.

---

## Results

The optimization process identified a combination of material properties and geometry that improved the predicted vibration performance of the structure.

The project received the **2024 Best Project Award** from the ONR Pipeline Program.

{% include image-gallery.html images="award.jpeg" height="500" %}

*2024 Best Project Award — Office of Naval Research Pipeline Program at Penn State Applied Research Laboratory.*

More importantly, the project taught me how to connect mechanical-engineering theory with a computational design process. The code was not the end product, it was a tool for making and defending an engineering decision.

---

## What I Learned

This project strengthened my understanding of how mass, stiffness, material selection, geometry, and boundary conditions influence structural behavior.

It also taught me how to organize a technical problem into design variables, constraints, calculations, and measurable results, then communicate the reasoning behind the final design.
