# UWB Real-Time Location System (RTLS) Documentation

Technical documentation and architectural specification for the Ultra-Wideband (UWB) Real-Time Location System (RTLS).

---

## Authors & Project Team

*Mechatronics Engineering, Faculty of Mechanical — Ho Chi Minh City University of Technology and Engineering (HCMUTE)*

* **Phuong Mai** ([@phuongmt08](https://github.com/phuongmt08)) — Lead Firmware & System Architect
* **Dong Son** — Project Co-Developer
* **Trung Quan** — Project Co-Developer

---

## Documentation Index

| Document | Description |
| :--- | :--- |
| **[Architecture Overview](./architecture.md)** | High-level system architecture and communication layers |
| **[Firmware Architecture](./firmware/overview.md)** | Core firmware stack, drivers, and power management |
| **[Ranging Protocol](./firmware/ranging_protocol.md)** | Double-Sided Two-Way Ranging (DS-TWR) state machine |
| **[Positioning Algorithms](./firmware/positioning_algorithms.md)** | On-device NLLS multilateration and Extended Kalman Filter (EKF) |
| **[Hardware Specifications](./hardware/schematics_and_specs.md)** | Anchor and Tag hardware specifications and block diagrams |
| **[Antenna Calibration](./hardware/antenna_calibration.md)** | Host-driven antenna delay calibration procedure |
| **[Software Tools](./software/rtls_studio_and_tools.md)** | UWB RTLS Studio GUI visualizer and device programmer utility |
| **[Deployment Guide](./deployment.md)** | 3D anchor placement geometry and NLOS mitigation |
