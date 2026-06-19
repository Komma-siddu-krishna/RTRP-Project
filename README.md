# IoT-Based Inverter for Autonomous Electric Vehicle Drive using CIPOS IPM

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform: Arduino](https://img.shields.io/badge/Platform-Arduino%20Uno-blue.svg)](https://www.arduino.cc/)

[cite_start]A Real-Time Research Project submitted in partial fulfillment of the academic requirements for the degree of **Bachelor of Technology in Computer Science and Engineering**[cite: 1, 2].

## 👥 Contributors & Affiliations
* [cite_start]**Lead Author:** K. Siddu Krishna (Reg No: 237R1A05DP / 237R1A05DJ) [cite: 2, 16]
* [cite_start]**Project Team Members:** K. Pooja (237R1A05DD), M. Rakshitha (237R1A05DP), K. Anand (237R5A05DF) [cite: 3]
* [cite_start]**Internal Guide:** Mrs. P. Santhuja (Assistant Professor) [cite: 2, 3]
* [cite_start]**Institution:** Department of Computer Science and Engineering, CMR Technical Campus (UGC Autonomous), Hyderabad, India[cite: 2].

---

## 📝 Document Abstract
[cite_start]Intelligent Power Modules (IPM) represent a fundamental evolution in motor control technology by consolidating power semiconductor devices (MOSFETs and IGBTs) alongside integrated control and protection circuits within a compact package[cite: 24, 25, 41]. 

[cite_start]This project implements an **IoT-enabled Inverter system** combined with **CIPOS IPM technology** specifically configured for autonomous Electric Vehicle (EV) drivetrains[cite: 1, 53]. [cite_start]This approach facilitates real-time sensor telematics, cloud-based analytics, and localized fault diagnostics to provide optimized motor performance, minimal operational downtime, and high-precision speed and thermal regulation[cite: 28, 29, 30].

---

## 📂 Sub-Directory Mapping
* [cite_start]**`docs/01_introduction.md`**: Broad project overview, context, and motivation behind shifting from traditional power converters to smart IPM networks[cite: 38].
* **`docs/02_lit_survey.md`**: Evaluation of 5 distinct 2023 IEEE research documents detailing state-of-the-art power tracking, predictive AI, and cloud telematics[cite: 38].
* [cite_start]**`docs/03_system_design.md`**: Comprehensive architectural assessment covering existing design constraints and the proposed multi-tier solution[cite: 38].
* [cite_start]**`docs/04_hardware.md`**: Structural review of physical components including ATmega328 register definitions and signal path configurations[cite: 38, 144].
* [cite_start]**`firmware/src/main.ino`**: Actual system core execution firmware featuring non-blocking logic loops, diagnostic filters, and LCD outputs[cite: 38, 440].
