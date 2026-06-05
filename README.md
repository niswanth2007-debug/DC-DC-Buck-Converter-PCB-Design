# DC-DC-Buck-Converter-PCB-Design# LM2596 DC-DC Buck Converter PCB Design

## Overview

This project presents the design and implementation of a DC-DC Buck Converter using the LM2596 switching regulator. The converter steps down a higher DC input voltage to a regulated 5V output while maintaining good efficiency.

The project was developed using KiCad and includes schematic capture, PCB layout, component footprint assignment, and 3D PCB visualization.

---

## Features

- LM2596 based buck converter
- Fixed 5V output
- Input power indication LED
- Screw terminal input/output connectors
- Through-hole component design
- Compact single-layer PCB layout

---

## Design Specifications

| Parameter | Value |
|------------|---------|
| Regulator IC | LM2596T-5 |
| Output Voltage | 5V |
| Inductor | 33 µH |
| Output Capacitor | 220 µF |
| Input Capacitor | 680 µF |
| Schottky Diode | 1N5822 |
| PCB Software | KiCad |

---

## Schematic

![Schematic](Images/Schematic.png)

---

## PCB Layout

![PCB Layout](Images/PCB_Layout.png)

---

## 3D View

### Top View

![3D Top](Images/PCB_3D_Top.png)

### Isometric View

![3D Angle](Images/PCB_3D_Angle.png)

---

## Bill of Materials

| Reference | Component |
|------------|-------------|
| U1 | LM2596T-5 |
| L1 | 33 µH Inductor |
| D1 | 1N5822 Schottky Diode |
| C1 | 680 µF Capacitor |
| C2 | 220 µF Capacitor |
| D2 | LED |
| R1 | 15 Ω Resistor |
| SW1 | Push Button |
| J1, J2 | Screw Terminal Connectors |

---

## Tools Used

- KiCad PCB Suite
- KiCad 3D Viewer

---

## Author

Niswanth B

Aspiring RF Engineer with interests in Embedded Systems, PCB Design, SDR, GNU Radio, and Wireless Communication Systems.
