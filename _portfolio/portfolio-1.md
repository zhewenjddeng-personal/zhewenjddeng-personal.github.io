---
title: "Reverse Leakage Current Tracking System"
excerpt: "A low-cost, high-capacity leakage current tracking system for solar cell degradation testing under ISOS-V3 conditions."
collection: portfolio
header:
  teaser: "ISOSV3_Fig1.png" # Thumbnail for the portfolio list
---

## Project Overview

The **ISOS-V3 Reverse Leakage Current Tracker** is designed to monitor the leakage current of solar cells or modules under stress conditions of: 
* **Environment:** 85% Relative Humidity (RH) and 85°C.
* **Conditions:** Dark environment with negative open-circuit voltage (-Voc) bias.
Users have the ability to vary the stress conditions as permitted by the testing equipments. 
### Cost-Effective Scaling
Off-of-the-shelf choices require expensive 4-quadrant source measuring units (SMUs) costing around **$6,000 per module**. (Can vary based on the supplier.) This system replaces that requirement with:
* **Low-cost power supplies:** ~$70 per module.
* **Current tracking modules:** ~$25 per module.

Additional cost includes a control PC, a data aquisition tool, and miscellaneous parts if needed.
This setup brings the cost down significantly, allowing for expansion of testing capacity for research labs and manufacturers.

---

## Hardware & Capacity
The current iteration is built to test **7 Devices Under Test (DUTs)** simultaneously.The modular design allows users to add additional low-cost testing slots as needed at **<$100/device**.

![Hardware Setup](ISOSV3_Fig1.png)
*Figure 1: The schematic of the wiring of the system for 1 DUT.*

![Hardware Setup](ISOSV3_Fig2.png)
*Figure 2: The physical setup of the full system.*

## Software Interface
The system includes a custom **Graphical User Interface (GUI)** that provides:
* Individual ON/OFF control for each testing slot.
* Real-time display of tracked leakage current.
* Data logging for long-term stability analysis.

![GUI Screenshot](/images/leakage-gui.png)
*Figure 2: The custom GUI used for real-time monitoring and control.*
