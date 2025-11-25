# 🌪️ Open-Source Modular Wind Tunnel Kit
> **A low-cost, fully 3D-printable wind tunnel for STEM education & aerodynamics research.** > *Designed by Team Jeju M-Tech (Jeju National University).*

[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
[![Status](https://img.shields.io/badge/Status-Active-success.svg)]()

---

## 📖 Introduction (소개)
The **Open-Source Modular Wind Tunnel Kit** is designed to solve the problem of expensive educational equipment. By utilizing FDM 3D printing, we reduced the manufacturing cost to **1/4 of commercial kits** while maintaining engineering reliability.

This project is perfect for:
* **STEM Education:** Teaching lift, drag, and fluid dynamics in schools.
* **Makers & Hobbyists:** Testing RC planes, drones, or 3D printed models.
* **Research:** Visualizing streamlines with smoke and measuring lift coefficients.

---

## ✨ Key Features (핵심 특징)
* **🏭 Fully 3D Printable:** All structural parts are designed to be printed on standard FDM printers (PLA/PETG).
* **🧩 Modular Design:** Easy to assemble/disassemble without glue. You can customize the test section for your needs.
* **💨 Flow Quality Control:** Includes a **Honeycomb** and **Screen** (57% porosity) to ensure uniform laminar flow.
* **📊 Smart Measurement:** Integrated **Beam Load Cell** & **Arduino** system to measure Lift force in real-time.
* **✅ Verified Performance:** Validated against NACA 0012 experimental data (Re ≈ 48k).

---

## 📂 Repository Structure (파일 구조)

```text
├── /3D Printed Wind Tunnel (by.jejumtech).zip         
│   ├── bed_AIO.ipt                # Source files (.ipt for Autodesk Inventor)
│   ├── cover_left(honey comb+screen).ipt
│   ├── cover_right(honey comb+fan+cover).ipt
│   ├── honey comb cover.ipt
│   ├── honey comb(left).ipt
│   ├── honey comb(right).ipt
│   └── OnePin_(Diameter=7.25).ipt
│   └── screen.ipt
│   └── (Reference_Only) # DO NOT PRINT
│       ├── fan.ipt
│       └── window.ipt
└── 3D Printed Wind Tunnel Assembly Manual.pdf
