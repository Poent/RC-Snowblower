# RC Snowblower Project

A remote-controlled snowblower project combining mechanical engineering, electronics, and software development.

## Project Status

This project began with the idea of adapting a tracked rover platform into a functional snowblower. Early work focused on selecting high-torque BLDC motors, ordering them for measurement, and designing a custom gearbox around them. Test chassis and drive experiments followed, including track design and multiple iterations of 3D-printed components.

Once the drivetrain was proven, attention shifted to CAD modeling in Fusion 360 and the integration of structural parts. A custom CNC aluminum frame was introduced, supported by interconnecting 3D-printed parts. Power requirements drove the selection of Headway 40152 LiFePO₄ cells (12S, 15 Ah, 75A continuous, 150A burst) configured in parallel packs.

Electronics design evolved in parallel. A custom controller board based on the ESP32 was developed to manage motor controllers (VESC 75100 units via CAN bus), linear actuators for blower lift, and lighting. The board design includes modular connectors, fusing, and provisions for telemetry and expansion sensors. Several iterations in KiCad have refined power distribution and signal integrity.

On the software side, development has focused on FreeRTOS-based task management, receiver input decoding (RadioMaster RP3 using CRSF), and CAN bus telemetry from the VESCs. Additional work includes LED logic, servo control, and the framework for telemetry feedback.

**Completed:**
- Chassis structure assembled with CNC aluminum frame and 3D-printed interconnects  
- Power system finalized around Headway LiFePO₄ cells and JK BMS (150A).
- Custom V1 of controller board - Designed, produced, soldered, and tested.
- Basic firmware running on ESP32 with input decoding and VESC telemetry working. 
- Initial testing of drivetrain and basic movement functions

**In Progress:**
- Finalize V1 Firmware for ESP32 and carrier board
- Design and implement universal mount for snowblower attachment. 
- Track stress testing and refinement
- Chassis cover design and integration (sealed against snow ingress) - NOT STARTED

**Future work:**
- Design blower attachment and integration.
- Preparing the project for public release (this repository) and planning documentation for CAD, electronics, and firmware.
- Refine parts list and BOM to reduce cost, complexity, and improve reliability.


## Overview
This repository will contain (wish list) the complete design and implementation files for a remote-controlled snowblower, including:

- **CAD Models**: 3D designs and mechanical components
- **Electronics**: Circuit designs, PCB layouts, and component specifications
- **Code**: Control software and firmware
- **Documentation**: Build guides, specifications, and user manuals
- **Images**: Photos, diagrams, and visual documentation
- **Build Log**: Chronological record of design iterations, testing, and modifications

## Repository Structure

```
├── CAD/           # 3D models, drawings, and mechanical designs
├── Code/          # Control software and firmware
├── Docs/          # Documentation and guides
├── Electronics/   # Circuit designs and electrical components
├── Images/        # Photos, diagrams, and visual documentation
└── Build_Log/    # Chronological record of design iterations and testing

```

## Features (Planned)
- [done] Remote control operation
- [done] Variable speed control
- [done] High-performance BLDC motors with custom gearboxes
- [ ] Weather-resistant design
- [ ] Modular component system
- [ ] Universal Mount for attachments (snowblower, plow, etc.)

### Wish List
- Autonomous navigation capabilities
- Real-time telemetry
- Produce fully open-source hardware and software
- Develop 3D printed versions of key components to reduce cost

## Hardware Requirements
*To be documented*

## Software Requirements
*To be documented*

## Getting Started
*Build instructions coming soon*

## Contributing
*Contribution guidelines to be added*

## License
*License information to be added*

## Contact
*Contact information to be added*

---
*This README will be updated as the project progresses.*