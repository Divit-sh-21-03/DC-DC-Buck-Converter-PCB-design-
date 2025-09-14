# LMR51450 DC-DC Buck Converter

This repository contains the complete KiCad design files for a DC-DC buck (step-down) converter using the Texas Instruments LMR51450 synchronous buck regulator. The design has been optimized for stable performance and low electrical noise (EMI).

## Key Specifications

* **Integrated Circuit:** Texas Instruments LMR51450
* **Input Voltage:** 10V - 35V DC
* **Output Voltage:** 7.6V DC
* **Maximum Output Current:** 4A
* **Switching Frequency:** Approximately 460 kHz

## Repository Contents

* **KiCad Project Files**: The project contains `.kicad_sch` (schematic), and `.kicad_pcb` (PCB layout) and `BOM` files.
* **Media**: This folder contains screenshots of the final schematic and PCB layout.

## Design Notes

The PCB layout was carefully designed to minimize EMI and ensure stable operation under high load. Key considerations include:
* Minimization of critical high-frequency current loop areas.
* Use of solid top and bottom ground planes for low-impedance current return paths.
* Strategic placement of input and output capacitors to reduce voltage ripple.
