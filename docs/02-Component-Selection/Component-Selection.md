---
---
title: Component Selection Example
---

**CPR Micro Metal Motor Encoders**

![Motor Test](image1.jpg)

| **Solution** | **Pros** | **Cons** |
|---|---|---|                                                                                              | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| ![](image1.jpg)<br>**Option 1.**<br>\* 100:1 Micro Metal Gearmotor LP 6V with 12 CPR Encoder<br>$29.95/each<br>\*[link to product](https://www.pololu.com/product/5112)                 | \* Lower no-load current reduces battery demand; smallest stall-current requirement; integrated encoder supports closed-loop position control; compact and lightweight.                                               | \* Lowest available torque; slower scanning; may struggle if the sensor mounting assembly is heavy or has substantial friction.<br> |
| ![](image2.jpg)<br>**Option 2.**<br>\* 100:1 Micro Metal Gearmotor MP 6V with 12 CPR Encoder <br>\* $29.95/each <br>\* [Link to product](https://www.pololu.com/product/5138) | \* Better torque and speed than LP; integrated encoder; moderate current requirement; same compact dimensions; good candidate for balancing performance and power. <br> | * Higher current than LP; requires closed-loop position control; may still need gearing or speed reduction for smooth scanning speed.                                                         |
| ![](image3.jpg)<br>**Option 3.**<br>\* 100:1 Micro Metal Gearmotor HP 6V with 12 CPR Encoder <br>\* $29.95/each <br>\* [Link to product](https://www.pololu.com/product/5164?utm_source=chatgpt.com) | \* Highest available torque; fastest motion; integrated encoder; better suited to mechanically demanding loads<br> | *Highest current consumption; more demanding driver and power-supply requirements; faster motion may require more careful acceleration and braking control.                                                         |

**Choice:** Option 2: Pololu 100:1 Micro Metal Gearmotor MP 6V with 12 CPR Encoder (Part #5138)

**Rationale:** The Pololu 100:1 Medium-Power Micro Metal Gearmotor is the preliminary selection for the scanning subsystem because it provides a balance between rotational speed, available torque, electrical current requirements, and physical size. Its 100.37:1 gearbox provides mechanical reduction, while its integrated quadrature encoder allows the PIC18F57Q43 microcontroller to monitor motor rotation and implement position feedback.

Compared to the low-power alternative, the medium-power motor offers increased torque and speed, which may improve its ability to move the LiDAR scanning assembly. Compared to the high-power alternative, it has a lower stall current, reducing the electrical demands on the motor driver and power system.

The motor is also compact and lightweight, making it a promising candidate for a handheld device. Final selection will depend on testing the scanning assembly's torque requirements, scan speed, encoder performance, and compatibility with the regulated motor supply.