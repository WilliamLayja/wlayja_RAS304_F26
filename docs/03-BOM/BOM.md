---
title: Bill of Materials
tags:
- tag1
- tag2
---


## Overview

This Bill of Materials (BOM) documents the electrical, electronic, and mechanical components required for the LiDAR motor and rotation-control subsystem. The system uses a motor, encoder, H-bridge motor driver, and Curiosity Nano microcontroller to control rotation and support LiDAR scanning.

Most electrical components are already available through TECH 162 or have been provided for the project. Additional components, including a slip ring, VL53L1X LiDAR sensor, and PLA filament, are included in the purchasing list.

## Bill of Materials

The following table lists the components from the KiCad schematic. All listed components are currently available through TECH 162 or have already been provided, resulting in no additional purchasing cost.

| Reference | Component / Description | Quantity | Source | Additional Cost |
|---|---|---:|---|---:|
| C1 | 0.33 µF Capacitor | 1 | TECH 162 | $0.00 |
| C2, C3, C4, C6, C7 | 0.1 µF Capacitor | 5 | TECH 162 | $0.00 |
| C5 | 47 µF Capacitor | 1 | TECH 162 | $0.00 |
| D1 | LED | 1 | TECH 162 | $0.00 |
| F1 | Fuse (Rating TBD) | 1 | TECH 162 | $0.00 |
| J1 | 6-Pin Motor/Encoder Connector | 1 | TECH 162 | $0.00 |
| J2 | 9–12V Power Input Connector | 1 | TECH 162 | $0.00 |
| J3 | Team Communication Connector | 1 | TECH 162 | $0.00 |
| J4 | Upstream Connector | 1 | TECH 162 | $0.00 |
| J5 | Downstream Connector | 1 | TECH 162 | $0.00 |
| J6 | GPIO & GND Connector | 1 | TECH 162 | $0.00 |
| J7 | LiDAR Connector | 1 | TECH 162 | $0.00 |
| J8 | External 5V Motor Power Connector | 1 | TECH 162 | $0.00 |
| JP1, JP2 | 2-Pin Jumpers | 2 | TECH 162 | $0.00 |
| R1 | 1 kΩ Resistor | 1 | TECH 162 | $0.00 |
| R2, R3, R4 | 10 kΩ Resistor | 3 | TECH 162 | $0.00 |
| R5, R6 | 4.7 kΩ Resistor (DNP) | 2 | TECH 162 | $0.00 |
| SW1 | Push Button Switch | 1 | TECH 162 | $0.00 |
| TP1–TP9 | Test Points | 9 | TECH 162 | $0.00 |
| U1 | FAN8100N H-Bridge Motor Driver | 1 | Already Provided | $0.00 |
| U2 | LM7805 Voltage Regulator | 1 | TECH 162 | $0.00 |
| WL1 | Curiosity Nano Microcontroller | 1 | Already Provided | $0.00 |

**Note:** R5 and R6 are marked DNP (Do Not Populate) and are not intended to be installed on the final PCB. The fuse rating remains to be verified.

## Components Requiring Purchase

The following components are needed for the LiDAR system and mechanical assembly. These items are not included in the provided electrical components.

| Component | Quantity | Supplier | Unit Cost | Total Cost |
|---|---:|---|---:|---:|
| Black Inland 1.75mm PLA Filament (2-Pack) | 1 | [Micro Center](https://www.microcenter.com/product/693159/inland-175mm-pla-basic-3d-printer-filament-2-pack-%e2%80%93-black) | $18.99 | $18.99 |
| 22mm 6-Wire Slip Ring | 1 | [Adafruit](https://www.adafruit.com/product/736) | $14.95 | $14.95 |
| ST VL53L1X LiDAR Sensor | 1 | [Holybro](https://holybro.com/products/st-vl53l1x-lidar) | $14.99 | $14.99 |
| **Total** | **3** | | | **$48.93** |

*All prices are based on the BOM spreadsheet. Shipping and taxes are not included.*

## Purchasing Summary

The majority of electrical components required for this subsystem are already provided through TECH 162, eliminating the need to purchase additional resistors, capacitors, connectors, microcontrollers, or motor-control hardware.

The remaining purchases consist of the slip ring, LiDAR sensor, and 3D-printing material.

- **Slip Ring:** Allows electrical connections to pass between the stationary and rotating sections of the LiDAR assembly.
- **VL53L1X LiDAR Sensor:** Provides time-of-flight distance measurements for object detection.
- **PLA Filament:** Used to manufacture custom mounting brackets, enclosures, and mechanical components for the LiDAR assembly.

The total additional component cost is **$48.93**, excluding shipping and applicable taxes.

## Component Datasheets

The following links provide technical information for major subsystem components.

| Component | Technical Documentation |
|---|---|
| FAN8100N Motor Driver | [Datasheet](https://rocelec.widen.net/view/pdf/1pizbjqffm/FAIRS23777-1.pdf?t.download=true&u=5oefqw) |
| LM7805 Voltage Regulator | [Datasheet](https://www.htckorea.co.kr/Datasheet/Voltage%20Regulator/LM78xx.pdf) |
| 6-Wire Slip Ring | [Datasheet](https://cdn-shop.adafruit.com/datasheets/SRC022A-6.pdf) |
| ST VL53L1X LiDAR Sensor | [Product Documentation](https://holybro.com/products/st-vl53l1x-lidar) |

## Final Notes

All components listed in the KiCad schematic have been documented in the Bill of Materials. Existing components are identified as provided materials, while additional components have been assigned suppliers and estimated costs.

Component footprints, final fuse rating, and part compatibility will be verified before PCB assembly and integration.
