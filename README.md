# Earthworm-Inspired Soft Microrobot Design (ME 685)

This repository presents the **conceptual design and system architecture of a bio-inspired soft microrobot** capable of peristaltic locomotion similar to an earthworm.

The project was developed as part of **ME 685 – Microrobotics** at Stevens Institute of Technology.  
It focuses on **mathematical modeling, actuator and sensor selection, and system-level design**, based on research literature, without physical fabrication.

---

## Project Overview

Soft robotics enables safe operation in **confined, unstructured, and delicate environments** where rigid robots are not suitable.

This project proposes a **microscale soft robot** designed for:

- biomedical applications (drug delivery, minimally invasive procedures)  
- aerospace inspection (tight mechanical structures)  
- confined-space navigation  

The robot mimics **earthworm locomotion (peristalsis)** using sequential contraction and expansion of body segments.

---

## Design Approach

Unlike traditional hardware projects, this work focuses on:

- **theoretical modeling**
- **component selection from research papers**
- **mathematical analysis of actuators and sensors**
- **complete system architecture design**

The full system was designed and validated analytically, including:

- actuator behavior modeling  
- sensor performance estimation  
- wireless power calculations  
- fabrication workflow planning  

---

## Bio-Inspired Locomotion

The robot replicates **peristaltic motion**, where:

- front segments anchor  
- middle segments contract  
- rear segments push forward  

This produces smooth crawling motion similar to an earthworm.

---

## System Architecture

The microrobot integrates multiple subsystems:

- **Shape Memory Alloy (SMA) actuators**
- **Piezoresistive force sensors**
- **Capacitive proximity sensors**
- **Wireless inductive power transfer**
- **Soft elastomer body structure**

---

## Actuation System (SMA-Based)

The robot uses **SMA bimorph actuators** for motion.

### Why SMA?

- compact and suitable for microscale  
- high strain capability  
- thermally driven (Joule heating)  
- enables soft deformation  

### Mathematical Modeling

Actuator bending is modeled using:

- curvature radius due to thermal mismatch  
- angular deflection  
- displacement calculations  

From the design:

- bending angle ≈ **10.2°**  
- horizontal displacement ≈ **1.6 µm**  
- vertical displacement ≈ **26.65 µm** :contentReference[oaicite:1]{index=1}  

 These values confirm feasibility of peristaltic motion at microscale.

---

## 📡 Sensor Design

### 1️⃣ Piezoresistive Sensor

Used to measure **strain and force** in the robot body.

- Force range: 0.1 – 3 mN  
- Resolution: < 5 µN  
- Bandwidth: 1 kHz  

Key concept:

- resistance change proportional to strain  
- implemented using **Wheatstone bridge** for signal amplification  

---

### 2️⃣ Capacitive Proximity Sensor

Used for **environment detection and obstacle sensing**.

- Detection range: 0–5 cm  
- Resolution: ≤ 1 mm  
- Response time: < 10 ms  

Key modeling:

- capacitance varies with distance (1/d relationship)  
- sensitivity increases at closer range  

---

## ⚡ Wireless Power Transfer

The robot is powered using **inductive coupling**, eliminating onboard batteries.

### Design Features:

- frequency: 200–300 kHz  
- induced voltage ≈ 19.6 V  
- output power ≈ **1.16 W** :contentReference[oaicite:2]{index=2}  

Advantages:

- continuous operation  
- compact design  
- suitable for micro-scale systems  

---

## CAD and Structural Design

A full CAD-based structural design was developed, including:

- actuator housing  
- spring-assisted structure  
- sensor placement  
- wiring paths  

The design ensures:

- modular integration  
- compatibility with SMA actuation  
- ease of fabrication  

---

## Proposed Fabrication Workflow

Although physical fabrication was not performed, a complete process was designed:

1. SMA actuator preparation  
2. Sensor fabrication and testing  
3. Mold design (3D printing / CNC)  
4. Elastomer casting  
5. Component integration  
6. Final curing and assembly  

This provides a clear path toward real-world implementation.

---

## What This Project Demonstrates

This project demonstrates strong understanding of:

- soft robotics design  
- bio-inspired locomotion  
- SMA actuator physics  
- sensor modeling (piezoresistive + capacitive)  
- wireless power transfer  
- system integration for microrobots  
- theoretical and analytical design methods  

---

## Applications

- targeted drug delivery  
- minimally invasive surgery  
- pipeline inspection  
- aerospace structure monitoring  
- confined environment exploration  

---

## Future Work

- closed-loop control using embedded electronics  
- autonomous navigation  
- improved energy efficiency  
- integration with onboard microcontrollers  
- physical prototyping and testing  

---

## Tools & Environment

- SolidWorks (CAD design)  
- MATLAB / analytical modeling  
- Research-based design methodology  
- Soft robotics and microrobotics literature  

---

## Reference Report

For complete technical details, equations, and design analysis, refer to:

**ME 685 Final Project Report**  
:contentReference[oaicite:3]{index=3}  

---

## License

MIT License
