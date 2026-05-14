# Environmental Analysis & Bioclimatic Tool Prototype

## Overview
This repository contains the development framework for a computational design tool focused on **Environmental and Bioclimatic Analysis**. Built on the principles of architecture in harmony with the environment, this tool leverages historical climate data and advanced geometric modeling to optimize building performance and occupant comfort.

The methodology is rooted in a professional practice that spans large-scale territorial studies (such as the 45-hectare analysis for **Rancho Los Frailes** in Valle de Bravo) to high-density urban modeling.

## Key Methodology (5-Step Process)
Based on the **Bioclimatic Design Framework**, the tool operates through the following stages:

1.  **Precise Geolocation:** Site definition using UTM coordinates for absolute spatial accuracy.
2.  **Climate Data Processing:** Integration of **EPW (EnergyPlus Weather)** files using 30-year historical typical day data to analyze radiation, wind, and temperature.
3.  **Terrain & Context Recreation:** High-fidelity modeling using contour lines, photogrammetry, or **LIDAR** 3D scans to capture the physical reality of the site.
4.  **Simulated Environmental Analysis:** Generation of project-specific studies including sun paths, radiation maps, and thermal comfort.
5.  **Evidence-Based Reporting:** Synthesis of environmental conditions into actionable design recommendations.

## Technical Stack
* **Platform:** Rhino 8 + Grasshopper
* **Simulation Engines:** * **Ladybug:** Weather data visualization, sun-path diagrams, and sky vault radiation.
    * **Honeybee:** Surface temperature mapping (Zone temperatures) and advanced thermal zones.
* **Core Concepts:** UTCI (Universal Thermal Climate Index), R-Values (Thermal Resistance), Albedo optimization, and Natural Hydrological Runoff.

## Recent Implementation: Rancho Los Frailes
* **Scale:** 45 Hectares.
* **Scope:** Territorial bioclimatic study identifying microclimates, slope analysis (Slope angle/Altimetry), and solar orientation to inform a master plan in Valle de Bravo.

## About the Author
**Javier Martínez Gaxiola** Computational Designer & Founder of **Dimensión N**.  
Expertise validated through direct training with **Chris Mackey** (Lead Developer of Ladybug Tools). This tool represents an intersection of academic rigor and professional architectural application.

---
*Developed for innovation in sustainable architecture.*
