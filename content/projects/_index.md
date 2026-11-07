---
title: Engineering Projects/"Portfolio"
---

Portfolio is a fairly corporate term and the captions are straight out of a resume, but the pictures are sloppy and unprofessional; I want to believe that reflects the candor of work I do for my own enjoyment

Also, **Software and system architectures are hard to take pictures of**, but here are some tangible things I've built. To any recruiters: there's more to the story in that regard, let's talk. LinkedIn in footer


Some projects are for university, some are for fun, many are both. All firmware and supplementary code for applicable projects was written completely by hand without AI assistance. I believe AI is well-suited and powerful in demanding business/productivity-centric settings where deliverables are everything, but that is not the case in a project fueled by curiosity and *love for the game*.

---

### Modernized Superheterodyne FM Radio Receiver
*04/2025*

Wrote embedded C firmware for Arduino Mega tuning a superheterodyne FM receiver via I2C 12-bit DAC, ADC RSSI feedback, and LCD interface with autonomous station acquisition across 88-108 MHz. Characterized VCO behavior using quartic regression over 56 measured data points (R² = 0.9987), enabling accurate digital frequency estimation and a DSP-assisted channel scan algorithm.

![FM Radio PCB](/portfolio-assets/image1.jpeg)
![FM Radio Test Setup](/portfolio-assets/image2.jpeg)

---

### Guitar Amplifier with Custom PCB
*12/2025*

Designed, manufactured, and engineered a miniature guitar amplifier featuring a custom PCB, bar-style LED visualizer, gain and output volume controls, low noise, USB power, and standard 1/4" mono input. Directed a small team utilizing system diagrams, functional decomposition, Gantt charts, critical path analysis, and circuit simulation in Multisim.

| | | |
|---|---|---|
| ![Amp Enclosure](/portfolio-assets/image3.jpeg) | ![Amp PCB](/portfolio-assets/image4.jpeg) | ![PCB Layout](/portfolio-assets/image5.png) |
| ![Oscilloscope Trace](/portfolio-assets/image6.png) | ![CAD Model](/portfolio-assets/image7.png) | ![Schematic](/portfolio-assets/image8.png) |
| ![Playing Amp](/portfolio-assets/image9.jpeg) | ![Wire Loom](/portfolio-assets/image10.png) | ![Assembly](/portfolio-assets/image11.jpeg) |

---
### Engine Monitoring Android App
*02/2024*

Developed a data-driven driver companion app for Android to aid in learning how to operate a manual transmission. Aggregated engine sensor parameters (OBD-II PIDs) over MQTT and processed this data within the app, including gear calculation from per-gear and final drive ratios.

| | | |
|---|---|---|
| ![App Dashboard](/portfolio-assets/image22.png) | ![Android Studio](/portfolio-assets/image23.jpeg) | ![MQTT Explorer](/portfolio-assets/image24.jpeg) |

---

### Embedded Sensor Control + BLE Interface
*04/2026*

Designed power electronics driver circuitry using MOSFETs and BJTs, regulated by a Raspberry Pi Pico running closed-loop PID firmware for real-time thermal control. Integrated Bluetooth Low Energy (BLE) serial communication for wireless setpoint configuration and live telemetry streaming.

![PID Breadboard Prototype](/portfolio-assets/image12.jpeg)
![Raspberry Pi Enclosure](/portfolio-assets/image13.jpeg)

---

### Hybrid Powertrain Simulation & Control Module
*06/2026 - 08/2026*

Drafted a bespoke hybrid architecture and control module integrating an existing ICE architecture with plug-in capable electric drive. Then learned more about MATLAB by onboarding into Simulink (a skill that proved very useful in a future DSP Lab) in order to model hybrid powertrain systems with MathWorks' Simscape HEV reference design.

![Architecture Sketch Front](/portfolio-assets/image38.jpeg)

---

### Industrial Control Systems & PLC Programming
*09/2025*

Built industrial control systems hands-on in lab and programmed PLCs using IEC 61131-3 standards. Developed detailed HMIs for Phoenix Contact PLCs with simulation before deployment using FactoryTalk Design Workbench, PLCnext Engineer, and Studio5000 across ladder logic, structured text, and function block diagram.

![PLC Training Station](/portfolio-assets/image14.jpeg)
![PLC Control Panel](/portfolio-assets/image15.jpeg)

---

### Various Lab Assignments
*2023-2025*

ATMega328p-based breakout board, temperature monitor and data logger with enclosure designed in Solidworks, PWM generation and parallel LCD test circuit (using registers, no library), audio amplifier perfboard, STM32 I2C implementation, op-amp class D amplifier.

| | | |
|---|---|---|
| ![Breakout Board](/portfolio-assets/image16.jpeg) | ![LCD Enclosure](/portfolio-assets/image17.jpeg) | ![Scope + Arduino](/portfolio-assets/image18.jpeg) |
| ![Audio Perfboard](/portfolio-assets/image19.jpeg) | ![Spectrum Analyzer](/portfolio-assets/image20.jpeg) | ![Class D Amp Scope](/portfolio-assets/image21.jpeg) |

---


### Li-ion Battery Cell Recycling & Validation
*10/2025*

Scrapped over 200 18650 cells from laptop batteries, tested all of their capacities and verified functionality using a multi-channel cell tester.

| | | |
|---|---|---|
| ![Charger + Cells](/portfolio-assets/image25.jpeg) | ![Cell Box](/portfolio-assets/image26.jpeg) | ![Cell Tester](/portfolio-assets/image27.jpeg) |

---

### Manual Transmission, Hypoid Differential & Viscous LSD Overhaul
*06/2025*

Disassembled and rebuilt a manual transmission to see how it worked and fix a $500 car. Vehicle was purchased with the transmission already uninstalled, then was rebuilt over the course of 3 months before being reinstalled.

| | | |
|---|---|---|
| ![Disassembled Transmission](/portfolio-assets/image28.jpeg) | ![Transmission Parts](/portfolio-assets/image29.jpeg) | ![Clutch Assembly](/portfolio-assets/image30.jpeg) |
| ![Flywheel](/portfolio-assets/image31.jpeg) | ![Ring Gear Diagram](/portfolio-assets/image32.png) | ![Reinstalled](/portfolio-assets/image33.jpeg) |

