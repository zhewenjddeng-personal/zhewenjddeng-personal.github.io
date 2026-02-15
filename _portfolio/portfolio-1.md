---
title: "Reverse Leakage Current Tracking System (ISOS-V3)"
excerpt: "A low-cost, high-capacity leakage current tracking system for solar cell degradation testing under ISOS-V3 conditions."
citation: "Zhewen J.D. Deng, Emily Munch, David P. Fenning (2025)"
collection: portfolio
header:
  teaser: "ISOSV3_Fig1.png" # Thumbnail for the portfolio list
hardwareurl: 'https://zhewenjddeng-personal.github.io/portfolio/portfolio-1/'
codeurl: 'https://github.com/fenning-research-group/Reverse_Leakage_Current_Traking-ISOS-V3.git'
additional_note: "(Python)"
---

## Project Overview

The **ISOS-V3 Reverse Leakage Current Tracker** is designed to study the impact of various device stack components on the longer term durability of the perovskite modules. The system monitors the leakage current of solar cells or modules in the µA range under user-defined stress conditions. In this project, the stress conditions are: 
* **Environment:** 85% Relative Humidity (RH) and 85°C.
* **Conditions:** Dark environment with negative open-circuit voltage (-Voc) bias.

### Cost-Effective Scaling
Off-of-the-shelf choices require expensive 4-quadrant source measuring units (SMUs) costing around **$6,000 per module**. (Can vary based on the supplier.) This system replaces that requirement with:
* **Low-cost power supplies:** ~$70 per module.
* **Current tracking modules:** ~$25 per module.

Additional cost includes a control PC, a data aquisition tool, and miscellaneous parts if needed.
This setup brings the cost down significantly, allowing for expansion of testing capacity for research labs and manufacturers.

---

## Hardware & Capacity
The current iteration is built to test **10 Devices Under Test (DUTs)** simultaneously. The modular design allows users to add additional low-cost testing slots as needed at **<$100/device**.

<p align="left">
  <img src="/images/ISOSV3_Fig1.png" width="400">
  <br>
  <em>Figure 1: The schematic of the wiring of the system for 1 DUT.</em>
</p>

<p align="left">
  <img src="/images/ISOSV3_Fig2.png" width="400">
  <br>
  <em>Figure 2: The physical setup of the full system.</em>
</p>

<p align="left">
  <img src="/images/ISOSV3_Fig3.png" width="450">
  <br>
  <em>Figure 3: The circuit box for tracking 10 DUTs concurrently. There are 7 boards mounted in the current figure. </em>
</p>

---

## Software Interface

The system includes a custom **Graphical User Interface (GUI)** that provides:
* **Real-time display of tracked leakage current.**
* **Data logging for long-term stability analysis.**

<p align="center">
  <img src="/images/ISOSV3_Fig4.png" width="1080">
  <br>
  <em>Figure 4: The custom GUI used for real-time monitoring and control. No device is currently connected in the shown image, thus the values show up as a straight line. Full code base see code. </em>
</p>

