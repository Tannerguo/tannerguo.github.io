---
title: "Vehicle Flap Lock Battery Upgrade"
excerpt: "Replacing disposable D-cell batteries with a rechargeable 18650 lithium-ion cell in a custom enclosure."
collection: portfolio
layout: single
gallery:
  - /images/flaplock1.jpg
  - /images/flaplockbatt1.jpg
  - /images/flaplockbatt2.jpg
  - /images/flaplockbatt3.jpg
  - /images/flaplockbatt4.jpg
  - /images/flaplockbatt5.jpg
  - /images/flaplockbatt6.jpg
  - /images/flaplock2.jpg
  - /images/flaplockbanner.jpg
---

## Project Overview

I own several **vehicle flap locks** to prevent unauthorized cars from entering our private driveway.  
These devices were originally sold with two power options:  

1. **Disposable battery-operated (D cells)**  
2. **Rechargeable Li-ion pack**  

I chose the **D-cell version** for easier maintenance and potential for future modifications. After nearly **two years of use**, the batteries died, which led me to design a rechargeable upgrade using reclaimed **18650 cells**.

## Process

When the flap lock stopped lowering, I initially tried:  

- Re-seating the Bluetooth dongle in my car  
- Unlocking repeatedly via the remote  
- Using a recorded sub-GHz signal on my Flipper Zero  

None of these worked — confirming the issue was a dead battery. Replacing two of the four D cells temporarily fixed it, but long-term replacement costs would be inefficient.

Instead, I built a rechargeable solution:

- **Calculated voltage requirements**  
  - Two D cells in series = ~3.0V nominal  
  - A single 18650 = ~3.7V nominal (within tolerance for modern electronics)  
- **3D Printed a custom enclosure** for an 18650 cell  
- **Integrated the rechargeable pack** into the flap lock housing  
- **Tested performance** to confirm reliable operation  

By reusing harvested laptop cells, the device now runs on a **rechargeable power source**, eliminating the need for costly disposable D Cells.

## Gallery

The following images show the original flap lock, the dead D cells, and the new 18650-based upgrade in its custom enclosure.
