# MeltyBrain PCB
### Custom printed circuit board for a Melty Brain Combat Robot

<img src="https://github.com/LunaWithARose/meltybrain-kicad/blob/main/images/melty-3d-front.png" width="40%">

## Overview

This project involves the design and development of a custom PCB for a Melty Brain combat robot.

A Melty Brain robot uses rotational motion to achieve directional movement and control. Unlike conventional robots, which rely on a fixed forward-facing orientation, a Melty Brain robot must account for its continuously changing orientation while spinning.

The goal of this project is to develop a compact electronics platform tailored to the requirements of a Melty Brain robot.

The PCB is designed around a **34 × 34 mm form factor**, with an emphasis on compact component placement, electrical reliability, and integration into the robot.

## Design Goals

- Develop a custom PCB tailored to the Melty Brain robot architecture.
- Maintain a compact 34 × 34 mm footprint.
- Consider electrical protection and power distribution.
- Design a board that can be integrated into a space-constrained combat robot.

## PCB Design

The board layout is being developed with consideration for component placement, routing, board dimensions, and electrical requirements.

### PCB Layout

<img src="https://github.com/LunaWithARose/meltybrain-kicad/blob/main/images/melty-front.png" width="40%">

*Top-side PCB layout showing component placement and routing.*

<img src="https://github.com/LunaWithARose/meltybrain-kicad/blob/main/images/melty-back.png" width="40%">

*Back-side PCB layout showing component placement and routing.*

<img src="https://github.com/LunaWithARose/meltybrain-kicad/blob/main/images/melty-3d-front.png" width="40%">
<img src="https://github.com/LunaWithARose/meltybrain-kicad/blob/main/images/melty-3d-back.png" width="40%">

*Three-dimensional rendering of the PCB.*

## Repository Structure
```
MeltyBrain-PCB/
│
├── README.md
│
├── images/
│       ├── melty-front.png
│       ├── melty-back.png
│       ├── melty-3d-front.png
│       └── melty-3d-back.png
│
├── hardware/
    ├── schematics
    └── pcbs
```

Directory structure is a suggested organization; adjust it to match the actual repository contents.

## Engineering Considerations

Several considerations are important throughout the design process:

- **Power distribution:** Ensuring that the board's power architecture accommodates the electrical demands of the robot.
- **Cost** Balancing component choice and demands with cost.
- **PCB layout:** Balancing component placement, routing, and board size.
- **Mechanical integration:** Ensuring the PCB fits within the robot's available space.
- **Reliability:** Designing with the operating environment and electrical stresses of a combat robot in mind.

## Development Progress

- [x] Initial PCB design
- [x] Component placement and layout development
- [x] Complete PCB routing
- [x] Design rule check (DRC)
- [x] Final schematic and layout review
- [ ] PCB fabrication
- [ ] Component assembly
- [ ] Electrical validation and testing
- [ ] Integration into robot

*Progress checklist reflects the current development stage and will be updated as the project advances.*

## Future Work

Future development will focus on preparing manufacturing files and validating the assembled board.

## Author

Designed and developed by **Luna Waller**.

Electrical Engineering Student | Washington State University

