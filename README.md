# RC Snowblower Project

A remote-controlled snowblower project combining mechanical engineering, electronics, and software development.

## Project Status

This project began with the idea of adapting a tracked rover platform into a functional snowblower. Early work focused on selecting high-torque BLDC motors, ordering them for measurement, and designing a custom gearbox around them. Test chassis and drive experiments followed, including track design and multiple iterations of 3D-printed components.

Once the drivetrain was proven, attention shifted to CAD modeling in Fusion 360 and the integration of structural parts. A custom CNC aluminum frame was introduced, supported by interconnecting 3D-printed parts. Power requirements drove the selection of Headway 40152 LiFePO₄ cells (12S, 15 Ah, 75A continuous, 150A burst) configured in parallel packs.

Electronics design evolved in parallel. A custom controller board based on the ESP32 was developed to manage motor controllers (VESC 75100 units via CAN bus), linear actuators for blower lift, and lighting. The board design includes modular connectors, fusing, and provisions for telemetry and expansion sensors. Several iterations in KiCad have refined power distribution and signal integrity.

On the software side, development has focused on FreeRTOS-based task management, receiver input decoding (RadioMaster RP3 using CRSF), and CAN bus telemetry from the VESCs. Additional work includes LED logic, servo control, and the framework for telemetry feedback.

# LATEST IMAGES
<img width="1291" height="881" alt="2025-09-27_19h33_31" src="https://github.com/user-attachments/assets/318b8e4a-360e-4173-9989-3fcac77bbc0d" />
<img width="1550" height="1101" alt="image" src="https://github.com/user-attachments/assets/f9479501-ae14-4d79-8e38-910c436204a8" />

![Sep 2025 Progress 02](https://github.com/user-attachments/assets/2a745e57-ded5-44e2-ac1e-f72b1d3ee798)
![Sep 2025 Progress](https://github.com/user-attachments/assets/e22fb218-9336-470e-b98d-70cce07f2b9d)

<img width="1699" height="1178" alt="2025-09-27_19h49_34" src="https://github.com/user-attachments/assets/39783cfe-64f6-49bb-95b7-1e906aa1ca03" />
<img width="1898" height="1193" alt="2025-09-27_19h50_09" src="https://github.com/user-attachments/assets/8798c63b-fc5e-4480-bb8b-b5eb331ac1b5" />
<img width="1362" height="876" alt="2025-09-27_19h51_03" src="https://github.com/user-attachments/assets/20652ad4-f598-415d-9c99-680e35195ad0" />

![PCB-blanks](https://github.com/user-attachments/assets/06fd5483-3e57-429e-97d3-9684ec6308cc)

![PCB-First-Boot](https://github.com/user-attachments/assets/9c4921ba-00f2-40e8-b488-200fb06e63de)


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
