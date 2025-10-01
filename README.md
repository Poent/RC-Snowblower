# RC Snowblower Project

<img width="1291" height="881" alt="2025-09-27_19h33_31" src="https://github.com/user-attachments/assets/318b8e4a-360e-4173-9989-3fcac77bbc0d" />

Hello everyone! Welcome to my crazy project.

Before diving into the details, here’s quick background on me and why I’m building this. Feel free to skip down to the status if you want the meat.

### Who I am
I’m a tech leader in the OT/MSP space with ~15 years in IT services. I own our MSP tool stack, cybersecurity program, and AI/automation initiatives. I’m CISSP-certified and studied electrical engineering, game development/design, and aviation management in college. I have a wonderful wife and two kids, and my hobbies include art, design, programming, 3D printing, woodworking, and more.

### How this project started
About two years ago my wife sent me a video of the Yarbo snowblower. It’s a tracked outdoor platform with attachments for mowing, snowblowing, hauling, etc., and it can go fully autonomous with an RTK/GNSS setup. I loved it… until I saw it was about $5,000, which I can’t justify for a <15-foot driveway.

Then she sent a smiliar (but different) 3D-printed snowblower video. Once again I was hyped to look at building it, but the "basic" kit alone was about $4,000. My dreams were dashed again—but the seed was planted.... I’ve got experience with CAD, 3D printing, and electronics, so I decided to try building my own!

That’s this project. While my BOM is under $4k... it is far more expensive than I initially anticipated and I have a far higher respect for those alternatives. 

### What to expect here
I can't honestly recommend anyone replicate this build. Better platforms exist, and I'm not an engineer! While I intend to make everything functional, resilient, and high quality... there WILL be problems. If you choose to follow along or, god forbid, try to build one of these yourself.... PLEASE understand what you're getting into. It WILL be a significant investment and there is NO garuntee of a working platform at the end of it. Please don't anticipate assistance of any kind if you choose to build this. BUT.... if you do... please tell me! I would love to see what other people do. I intend to make and keep this project fully open source, and I have no dreams of making this into a commercial product at any point in time. 

For those of you that want to just check it out and/or follow along - then sit back, and enjoy the ride!


## Status

**Completed**
- Chassis assembled with CNC aluminum frame and 3D-printed interconnects
- Power system using Headway 40152 LiFePO₄ cells and JK BMS
- V1 controller board designed, produced, soldered, and tested
- Basic ESP32 firmware with CRSF input and VESC CAN telemetry
- Initial drivetrain movement tests

**In Progress**
- Finalizing V1 firmware for the ESP32 and carrier board
- Universal mount for the snowblower attachment
- Track stress testing and refinement
- Chassis cover design and integration (sealed against snow)

**Planned**
- Blower attachment design and integration
- Public-ready docs for CAD, electronics, and firmware
- BOM refinement for cost and reliability

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

# Progress

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
