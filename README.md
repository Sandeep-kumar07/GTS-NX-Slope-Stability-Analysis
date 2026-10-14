# GTS-NX-Slope-Stability-Analysis
Academic GTS NX project: 2D finite element slope stability analysis using MIDAS GTS NX under rainfall and pseudo-static loading conditions.
# Analysis of Soil Slope Stability With and Without Reinforcement Using MIDAS GTS NX

![MIDAS GTS NX](https://img.shields.io/badge/Software-MIDAS%20GTS%20NX-blue)
![Civil Engineering](https://img.shields.io/badge/Domain-Civil%20Engineering-orange)
![Geotechnical Engineering](https://img.shields.io/badge/Field-Geotechnical%20Engineering-green)
![FEM](https://img.shields.io/badge/Method-Finite%20Element%20Method-red)

## 📌 Overview

This project presents a numerical investigation of **soil slope stability using MIDAS GTS NX**, a finite-element-based geotechnical analysis software.

The study investigates the stability and deformation behaviour of a soil slope under different loading and environmental conditions. Two primary configurations are analysed:

1. **Slope without reinforcement**
2. **Slope with soil-nail reinforcement**

Additional analyses are performed to investigate the effects of:

- Self-weight loading
- Rainfall infiltration
- Pseudo-static loading
- Soil-nail reinforcement

The stability of the slope is evaluated using the **Strength Reduction Method (SRM)**, with particular emphasis on the **Factor of Safety (FOS)**, shear strain behaviour, stress distribution, and reinforcement forces.

---

## 🎯 Objectives

The main objectives of this project are:

- To analyse the stability of a soil slope **with and without reinforcement**.
- To investigate slope behaviour under **self-weight, rainfall, and pseudo-static loading**.
- To evaluate the **Factor of Safety (FOS)** using the Strength Reduction Method.
- To study stress, strain, displacement, and deformation behaviour of the slope.
- To evaluate the forces developed in the soil-nail reinforcement.
- To compare the stability of reinforced and unreinforced slope configurations.
- To investigate the influence of rainfall on slope stability.

---

## 🏗️ Model Geometry

The slope was developed as a **2D plane-strain finite element model** in MIDAS GTS NX.

The model consists of:

- Foundation soil
- Embankment soil
- Sloping geometry
- Soil-nail reinforcement
- Boundary constraints

The basic model geometry was created using polylines.

### Geometry Dimensions

The numerical model was constructed using the following principal coordinates:

```text
(0, 0)
(65, 0)
(65, 20)
(65, 35)
(45, 35)
(25, 20)
(0, 20)
(0, 0)
