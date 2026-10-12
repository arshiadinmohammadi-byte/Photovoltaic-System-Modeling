# Photovoltaic System Modeling and Performance Analysis

## Overview

This project focuses on the modeling, simulation, and performance analysis of a photovoltaic (PV) system using **PVsyst, TRNSYS, and SolidWorks**. The objective is to investigate the electrical performance of photovoltaic modules under different solar irradiance conditions, evaluate system configuration options, and analyze the effects of shading on overall system performance.

The project combines electrical simulation, PV system design, and three-dimensional geometric modeling to provide a comprehensive assessment of photovoltaic system behavior.

## Objectives

* Model photovoltaic module performance under different solar irradiance levels.
* Analyze current–voltage (I–V) characteristics under varying operating conditions.
* Simulate photovoltaic system performance using TRNSYS.
* Design and arrange PV modules using SolidWorks.
* Evaluate inverter configurations and system compatibility in PVsyst.
* Investigate shading effects and their impact on energy production.
* Assess overall system performance using the performance ratio (PR).

## Software and Tools

* **PVsyst** — PV system design, configuration, shading analysis, and performance evaluation.
* **TRNSYS** — Time-dependent simulation of photovoltaic module behavior.
* **MATLAB** — Numerical calculations and data analysis, where applicable.
* **SolidWorks** — Two-dimensional modeling and panel arrangement.

## System Configuration

### Photovoltaic Module

The simulations use the **VSUN450-144BMH photovoltaic module**, with a nominal power rating of 450 W.

### TRNSYS Simulation

The photovoltaic module's electrical behavior was investigated under three solar irradiance conditions:

* 1000 W/m²
* 800 W/m²
* 600 W/m²

The simulation was configured with a 60-hour stopping time and a time step of 0.01 hours. The resulting I–V characteristics were used to examine the influence of irradiance on module performance.

### PVsyst System Design

The PV system was modeled in PVsyst to evaluate system configuration and performance. Different inverter arrangements were considered, including a configuration using six 3 kW multi-MPPT inverters and an alternative arrangement using two inverters with ten modules per inverter.

The simulations were used to assess inverter compatibility, system losses, and overall energy performance.

### Geometric Modeling and Shading Analysis

SolidWorks was used to develop a two-dimensional arrangement of the photovoltaic panels. The modeled configuration consists of **14 panels in the horizontal direction and 17 panels in the vertical direction**.

Shading analysis was performed for the winter solstice, December 21, at 3:00 PM to investigate the effect of solar position and geometric shading on the PV array.

## Key Results

The PVsyst simulation produced the following performance indicators:

| Parameter              |         Result |
| ---------------------- | -------------: |
| PV module              | VSUN450-144BMH |
| Shading loss           |           1.3% |
| Performance ratio (PR) |         83.11% |

These results provide an initial assessment of the system's performance under the modeled conditions. The performance ratio reflects the overall effectiveness of the PV system, while the shading loss quantifies the estimated impact of shading in the simulated configuration.

## Repository Structure

```text
photovoltaic-system-modeling/
├── README.md
├── TRNSYS/
│   ├── model_files/
│   └── results/
├── PVsyst/
│   ├── project_files/
│   └── reports/
├── SolidWorks/
│   ├── CAD_files/
│   └── renders/
├── MATLAB/
│   └── scripts/
└── figures/
    ├── iv_curves/
    ├── system_layout/
    └── shading_analysis/
```

The folder structure is a suggested organization. Modify it to match the files included in the repository.

## Applications

This project demonstrates the application of numerical simulation, photovoltaic system design, electrical performance analysis, and three-dimensional modeling to renewable energy engineering.

## Author

**Arshia Din Mohammadi**

Mechanical Engineering — University of Tehran

Research interests: Renewable Energy, Energy Conversion, Thermal Systems, and Computational Modeling.

---

*This repository contains simulation models, design files, and results associated with photovoltaic system analysis. Results depend on the assumptions, input data, and configurations used in each simulation.*
