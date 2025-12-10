---
layout: project
title: Design a Torque Wrench, by David Almeida and Kate Ruelan
description: Using given specifications, chose a material that satisfies all factor-of-safety and performance requirements, and modeled the system in Ansys.
technologies: [Autodesk Fusion, Ansys, Matlab]
image: /assets/images/CAD-model-of-torque-wrench-from-Fusion-360.png
---

# Torque Wrench Design Project

## 1. CAD Model
The figure below shows the initial CAD model of the torque wrench.

<div align="center">
  <img src="{{ 'assets/images/CAD-model-of-torque-wrench-from-Fusion-360.png' | relative_url }}" width="350"/>
  <p><em>Figure 1. CAD Model of Torque Wrench</em></p>
</div>

---

## 2. Material Selection: Titanium Alloy (Ti-12Mo-6Zr-2Fe)

**Selected Material:**  
**Titanium, beta alloy — Ti-12Mo-6Zr-2Fe**

**Material Properties:**
- Elastic Modulus, E = 9.16–13.1 × 10⁶ psi  
- Poisson’s Ratio = 0.31–0.35  
- Yield Strength = 130–157 × 10³ psi  
- Fatigue Strength at 10⁷ cycles = 69.2–86.8 × 10³ psi  
- Fracture Toughness, KIC = 80.1–83.7 × 10³ psi√in  

<div align="center">
  <img src="{{ 'assets/images/Screenshot-Granta_software.png' | relative_url }}" width="300"/>
  <p><em>Figure 2. Titanium Alloy Comparison (from Granta)</em></p>
</div>

The material was selected for its high yield strength, favorable fatigue characteristics, and lower density compared to steel alloys.

---

## 3. Loads, Boundary Conditions, and Strain Gauge Placement

### Boundary Conditions
- The **tip of the body of the drive** was modeled as the *stationary support*.
- The **end face of the handle** was the *applied force location* where maximum deflection occurs.

<div align="center">
  <img src="{{ 'assets/images/boundary-conditions-diagram.jpg' | relative_url }}" width="320"/>
  <p><em>Figure 3. Loads and Boundary Conditions</em></p>
</div>

### Strain Gauge Placement
<div align="center">
  <img src="{{ 'assets/images/strain-gauge-location-on-torque-wrench.png' | relative_url }}" width="320"/>
  <p><em>Figure 4. Strain Gauge Location on Wrench Body</em></p>
</div>

---

## 4. Finite Element Analysis Results

### Normal Strain Contours
<div align="center">
  <img src="{{ 'assets/images/Normal-strain-contours.png' | relative_url }}" width="320"/>
  <p><em>Figure 5. Normal Strain Contours</em></p>
</div>

### Maximum Principal Stress Contours
<div align="center">
  <img src="{{ 'assets/images/principal-stress-contours.png' | relative_url }}" width="320"/>
  <p><em>Figure 6. Maximum Principal Stress Contours</em></p>
</div>

---

## 5. Summary of FEM Numerical Results
- **Maximum Normal Stress:** 52,714 psi  
- **Strain at Strain Gauge:** 1308.4 microstrain  
- **Maximum Deflection:** 0.48383 in  

### Strain Gauge and Sensitivity
- **Calculated Sensitivity:** 1.3084 mV/V  
- **Selected Strain Gauge:** *SGT-2LH/350-TY11*  
- **Gauge Type:** Half-bridge  
- **Dimensions:** Width = 0.158 in, Length = 0.563 in  

---

## 6. Summary
This project involved selecting a high-performance titanium alloy, modeling the torque wrench in Autodesk Fusion and Ansys, and analyzing stress, strain, and deflection behavior under realistic loading conditions. The chosen material and design meet the factor-of-safety and deflection requirements and allow effective strain measurement using the specified gauge.

