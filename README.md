<div align="center">

# Crabby · FTC 9384 Competition Robot

### FTC Team 9384 Hydraulic Hydras · 2022–2023 POWERPLAY Season Robot CAD

[![FTC Team](https://img.shields.io/badge/FTC-Team_9384_Hydraulic_Hydras-00aeef?style=flat-square&logo=first&logoColor=white)](https://ftc-events.firstinspires.org/team/9384)
[![Season](https://img.shields.io/badge/Season-2022--2023_POWERPLAY-8b5cf6?style=flat-square)](#the-challenge)
[![CAD](https://img.shields.io/badge/CAD-STEP_Assemblies-22c55e?style=flat-square)](#cad-files)
[![GrabCAD](https://img.shields.io/badge/GrabCAD-Public_Model-f57c00?style=flat-square)](https://grabcad.com/library/ftc-9384-2022-2023-robot-1)
[![License](https://img.shields.io/badge/License-CC_BY_4.0-f59e0b?style=flat-square)](LICENSE)

<picture>
  <img src="media/site/final-bot-v9.png" alt="CAD render of Crabby, FTC Team 9384's POWERPLAY robot" width="820" draggable="false">
</picture>

Open mechanical design solid models, competition photography, design history, and subsystem CAD for FTC Team 9384's POWERPLAY robot.

[Robot Overview](#overview) | [Design History](docs/design-history.md) | [CAD Files](#cad-files) | [Competition Gallery](#project-media) | [GrabCAD Model](https://grabcad.com/library/ftc-9384-2022-2023-robot-1)

</div>

---

## Overview

**Crabby** was FTC Team 9384 Hydraulic Hydras' official competition robot for the 2022–2023 **POWERPLAY** season. Across three major competition iterations, the team developed an omnidirectional Mecanum drive base, dual cascading linear slide lift, compliant cone claw, and a compact direct-drive coaxial turret.

The defining mechanical innovation was the directly driven turret: placing the drive motor output shaft concentric with the center of turret rotation allowed the scoring lift and claw to aim at junction poles independently from chassis orientation, drastically reducing cycle times.

| Subsystem Specification | Technical Implementation |
| --- | --- |
| Drivetrain architecture | 4-wheel independent Mecanum drive with bevel gear wheel pods |
| Turret mechanism | Concentric direct-drive motor axis with large-diameter ring bearing |
| Vertical lift | Dual cascading REV linear slides with high-speed pulley rigging |
| End-effector claw | Active compliant servo gripper with conical wedge retention |
| Structural frame | Custom CNC machined aluminum plates and reinforced structural standoffs |
| Iteration milestones | 3 competition versions documented from Kickoff to State Championship |

## The Challenge

In the [POWERPLAY](https://www.youtube.com/watch?v=HsitvZ0JaDc) game, robots collected conical game elements and stacked them on vertical junction poles of varying heights (Low, Medium, High). Crabby was engineered to satisfy strict competition constraints:
- Full 3-DOF planar mobility to maneuver around dense junction forests.
- 33+ inch vertical reach to cap high junction goals.
- Rapid 360° turret targeting to score without rotating the drivetrain.

## Mechanical Evolution

| Phase | Competition Milestones | Mechanical Evolution |
| :---: | --- | --- |
| **Stage 1** | Kickoff to Qualifier 4 | H-frame Mecanum chassis, single REV linear slide, and two-servo compliant wheel intake. |
| **Stage 2** | Qualifier 4 to Super Qualifier | High-speed slide drive gearing, revised pinch claw, and concentric direct-drive turret. |
| **Stage 3** | Super Qualifier to State Championship | Dual-slide reinforced mast, enlarged turret bearing, bevel drivetrain, and lowered center of gravity. |

Read the in-depth mechanism failure mode analysis in [`docs/design-history.md`](docs/design-history.md).

## Project Media

<div align="center">

| Crabby Scoring on High Junction | Driving in Competition Traffic |
| :---: | :---: |
| <img src="media/site/img_2019.jpg" width="100%" alt="Crabby scoring a cone on a junction"> | <img src="media/site/img_2020.jpg" width="100%" alt="Crabby driving near a junction during competition"> |

</div>

<div align="center">

| Pit Fabrication & Tuning | Concentric Direct-Drive Turret |
| :---: | :---: |
| <img src="media/site/20230204_192015.jpg" width="100%" alt="Team members working on Crabby"> | <img src="media/site/img_0029.jpg" width="100%" alt="Top view of Crabby's direct-drive turret"> |

</div>

<div align="center">

| Compliant Cone Claw CAD | Completed Competition Robot |
| :---: | :---: |
| <img src="media/site/gripper-v117.png" width="100%" alt="CAD render of Crabby's cone claw"> | <img src="media/site/img_1451.jpg" width="100%" alt="Front view of the completed Crabby robot"> |

</div>

## CAD Files

Neutral ISO 10303 STEP exports compatible with Fusion 360, Onshape, SolidWorks, and Inventor:

| Subsystem File | Contents & Assemblies |
| --- | --- |
| [`final bot.step`](cad/final%20bot.step) | Master robot competition assembly |
| [`Chassis.step`](cad/Chassis.step) | Mecanum drive base and chassis frame |
| [`intake.step`](cad/intake.step) | Compliant cone intake and gripper |
| [`regular lifts.step`](cad/regular%20lifts.step) | Primary linear slide lift stage |
| [`inverted lift.step`](cad/inverted%20lift.step) | Inverted auxiliary slide rigging |
| [`turret assembled.step`](cad/turret%20assembled.step) | Concentric direct-drive turret assembly |

> [!NOTE]
> Large assembly files are tracked via Git LFS. Run `git lfs install && git lfs pull` after cloning.

## License & Attribution

Original CAD models, photographs, and documentation © 2022–2026 **Angelo Demetroulakos**. Licensed under the **[Creative Commons Attribution 4.0 International License](LICENSE)**.

```text
Based on the FTC 9384 2022–2023 Robot (Crabby) by Angelo Demetroulakos and FTC Team 9384 Hydraulic Hydras,
licensed under CC BY 4.0. Source: https://github.com/AloeVeraZ/FTC9384-2023-Robot-Crabby
```

---

<div align="center">

Built by **FTC Team 9384 · Hydraulic Hydras** · Documented by **[Angelo Demetroulakos](https://angelojamesny.com)**

</div>
