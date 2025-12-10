---
layout: project
title: Design a Torque Wrench, by David Almeida and Kate Ruelan
description: Using given specifications, chose a material that satisfies all of the factor of safety, and performance requirements, and model on Ansys
technologies: [Autodesk Fusion, Ansys, Matlab]
image: /assets/images/CAD-model-of-torque-wrench-from-Fusion-360.png
---

The torque wrench design on CAD is shown in the first image

Material selected for torque wrench: 
Titanium, beta alloy, Ti-12Mo-6Zr-2Fe
E = 9.16 - 13.1 E6 psi
poissons ratio = 0.31 - 0.35
y = 130 - 157 E3 psi
Fatigue strength at 10E7 cycles = 69.2 - 86.8 E3 psi
KIC = 80.1 - 83.7 E3 psi in^0.5 

![Shaded rendering of earlier version]({{"assets/images/Screenshot-Granta_software.png" | relative_url }}){:.inline-image-r style="width: 200px"}
The second image shows how this alloy of Titanium compares to other alloys of Titanium as well as alloys of Steel and Aluminum.

Loads and Boundary Conditions, and strain gauge location are on the third image. 
As indicated in the third image, the tip of the body of the drive was chosen to be the stationary anchor in Ansys. The face of the tip of the handle was chosen to be where the force is applied and thus the maximum deflection. 
![Shaded rendering of earlier version]({{"assets/images/boundary-conditions-diagram.jpg" | relative_url }}){:.inline-image-r style="width: 200px"}

The fourth image shows the location of the strain gauge.
![Shaded rendering of earlier version]({{"assets/images/strain-gauge-location-on-torque-wrench.png" | relative_url }}){:.inline-image-r style="width:200px"}

The fifth image shows the Normal Strain Contours.
![Shaded rendering of earlier version]({{"assets/images/Normal-strain-contours.png" | relative_url }}){:.inline-image-r style="width:200px"}

The sixth image shows the Maximum Principal Stress Contours.
![Shaded rendering of earlier version]({{"assets/images/principal-stress-contours.png" | relative_url }}){:.inline-image-r style="width:200px"}


Summary of numerical results of FEM:
Maximum normal stress: 52,714 psi
Strain at the gage: 1308.4  microstrains
DeflectionMax: 0.48383 in 

Torque Wrench Sensitivity in mV/V using strain from FEM analysis: 1.3084 mV/V
Strain Gauge Selected: SGT-2LH/350-TY11 We chose a half bridge strain gauge design with a width of 0.158 in and a length of 0.563 in.
