---
layout: project
title: Design a Torque Wrench, by David Almeida and Kate Ruelan
description: Using given specifications, chose a material that satisfies all of the factor of safety, and performance requirements, and model on Ansys
technologies: [Autodesk Fusion, Ansys, Matlab]
image: /assets/images/Normal-strain-contours.png
---

The torque design on CAD is shown below:
/assets/images/CAD-model-of-torque-wrench-from-Fusion-360.png

Material selected for torque wrench: 
Titanium, beta alloy, Ti-12Mo-6Zr-2Fe
E = 9.16 - 13.1 E6 psi
 = 0.31 - 0.35
y = 130 - 157 E3 psi
Fatigue strength at 10E7 cycles = 69.2 - 86.8 E3 psi
KIC = 80.1 - 83.7 E3 psiin1/2 

/assets/images/Screenshot-Granta_software.png
Above shows how this alloy of Titanium compares to other alloys of Titanium as well as alloys of Steel and Aluminum.

Loads and Boundary Conditions, and strain gauge location: 
As indicated in the picture below, the tip of the body of the drive was chosen to be the stationary anchor in Ansys. The face of the tip of the handle was chosen to be where the force is applied and thus the maximum deflection. 
/assets/images/boundary-conditions-diagram.jpg
Below is an image showing the location of the strain gauge:
/assets/images/strain-gauge-location-on-torque-wrench.png

Normal Strain Contours:
/assets/images/Normal-strain-contours.png

Maximum Principal Stress Contours:
principal-stress-contours.png

Summary of numerical results of FEM:
Max, Normal : 52,714 psi
Gage: 1308.4  strains
DeflectionMax: 0.48383 in 

Torque Wrench Sensitivity in mV/V using strain from FEM analysis: 1.3084 mV/V
Strain Gauge Selected: SGT-2LH/350-TY11 We chose a half bridge strain gauge design with a width of 0.158 in and a length of 0.563 in.
