# Earthworm-Inspired Soft Microrobot Design

This repository presents the **conceptual design and system architecture of a bio-inspired soft microrobot** capable of peristaltic locomotion similar to an earthworm.

The project was developed as part of the **Microrobotics Final Project (ME-685)** at **Stevens Institute of Technology**. The work focuses on **actuator selection, sensor integration, wireless power delivery, and CAD-based system design** for a soft robotic platform intended for confined-space applications.

---

## Authors

Bhagyath Badduri  
Mohammad Althaf Syed  
Sai Likhit Nuvvala  

Department of Mechanical Engineering  
Stevens Institute of Technology

---

# Project Overview

Soft robotics enables robots to operate safely in **unstructured and confined environments** where traditional rigid robots cannot function effectively.

This project proposes an **earthworm-inspired microrobot** designed for:

• Biomedical applications  
• Aerospace inspection  
• Navigation through narrow or complex environments  

The robot uses **peristaltic locomotion**, where body segments contract and expand sequentially to produce forward motion.

---

# Robot Concept

![Robot Concept](robot_concept.gif)

The microrobot integrates multiple subsystems:

• Shape Memory Alloy (SMA) actuators  
• Piezoresistive force sensors  
• Capacitive proximity sensors  
• Wireless inductive power transfer  
• Soft elastomer robot body

---

# Actuation System

![SMA Actuator](images/sma_actuator.png)

The robot uses **Shape Memory Alloy (SMA) bimorph actuators** to generate motion.

Key features:

• Compact actuation for micro-scale robots  
• Large deformation capability  
• Thermal activation using Joule heating  
• Suitable for soft robotic locomotion

The bending occurs due to **thermal expansion mismatch between NiTi and aluminum layers**, generating controlled curvature.

---

# Sensor Design

## Piezoresistive Sensor

![Sensor Circuit](images/sensor_circuit.png)

Used for measuring mechanical strain and force applied to the robot body.

A **Wheatstone bridge configuration** amplifies small resistance changes caused by deformation.

Specifications:

| Parameter | Value |
|-----------|------|
Force range | 0.1 – 3 mN |
Resolution | < 5 µN |
Bandwidth | 1 kHz |

---

# Wireless Power Transfer

![Wireless Power](images/wireless_power.png)

The robot receives power through **inductive wireless energy transfer**.

Advantages:

• Eliminates bulky onboard batteries  
• Enables continuous operation  
• Suitable for micro-scale robots

Typical parameters:

Transmission frequency: **200–300 kHz**  
Output power: **~1.16 W**

---

# CAD Model

![CAD Model](images/cad_model.png)

A **SolidWorks CAD model** was created to design the microrobot structure.

The model includes:

• Cylindrical actuator housing  
• Spring-assisted structure  
• Sensor mounting locations  
• Electrical wiring paths

---

# Proposed Fabrication Process

Although the robot was **not physically fabricated**, the complete fabrication workflow was designed.

Steps:

1. SMA actuator preparation  
2. Sensor preparation  
3. Mold fabrication  
4. Elastomer casting  
5. Actuator integration  
6. Sensor embedding  
7. Final casting and curing

---

# Applications

Potential applications include:

• Targeted drug delivery  
• Minimally invasive medical procedures  
• Aerospace structure inspection  
• Pipeline monitoring  
• Confined-space exploration

---

# Future Work

Future improvements could include:

• Embedded microcontroller integration  
• Closed-loop locomotion control  
• Improved wireless power efficiency  
• Autonomous navigation

---

# License

MIT License
