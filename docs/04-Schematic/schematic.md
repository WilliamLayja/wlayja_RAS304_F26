---
title: Schematic
---

## Overview

This schematic is designed to control the rotational movement of a 360-degree LiDAR scanning system. The subsystem uses a 25SG-370CA-78-EN DC gear motor with an integrated encoder to rotate the LiDAR sensor continuously while tracking its angular position.

The PIC18F57Q43 Curiosity Nano serves as the main controller, sending signals to a FAN8100N H-bridge motor driver to control the motor's movement. The encoder provides feedback to the microcontroller, allowing the system to monitor rotational speed and estimate angular position.

The schematic also includes a 5V linear voltage regulator (LM7805), power filtering capacitors, a fuse, debugging components, and connectors for communication with other team subsystems. The motor driver requires a separate, compatible motor supply.

This subsystem will support the team's overall LiDAR system by providing continuous rotational movement and encoder feedback for coordinating distance measurements.


![schematic](Subsystem_Schematic_Design.png){style width:"350" height:"300;"}
**Figure 1:** Showing a example schematic.


## Resouces

The schematic as a PDF download is available [*here*](Subsystem_Schematic_Design.pdf), and the Zip folder of the project [*here*](Subsystem_Schematic_Design.zip).