# 🦅 Yogesh E S | UAV Autonomy & Bare-Metal Avionics Systems Engineer

<div align="center">
  <a href="https://yogesh031020.github.io/">🌐 **Deep-Dive Systems Portfolio (yogesh031020.github.io)**</a>
  <br><br>

  ![Avionics & Control](https://img.shields.io/badge/System--Rigor-Embedded%20C%2B%2B%20%7C%20Control%20Theory-blue?style=for-the-badge&logo=c%2B%2B)
  ![ROS 2 Architecture](https://img.shields.io/badge/Autonomy-ROS%202%20Jazzy%20%7C%20PX4%20%7C%20ArduPilot-green?style=for-the-badge&logo=ros)
  ![Hardware Engineering](https://img.shields.io/badge/Hardware-PCB%20Design%20%7C%20Aero%20Design%20(CAD%2FFEA)-orange?style=for-the-badge&logo=kicad)
</div>

---

### 🛸 Executive Technical Summary
A systems-focused **Aeronautical & Robotics Engineer** with **2+ years of industrial aerospace experience** at *Novatech Robo Pvt Ltd*. I bridge the gap between high-speed hardware design and low-level control firmware. 

My work focuses on co-designing physical avionics (**custom flight controller PCBs**), writing highly deterministic, multitasking embedded C++ (**FreeRTOS, MAVLink, uORB**), and implementing high-level autonomous navigation stacks (**ROS 2, EKF3 Sensor Fusion, A\* Path Planning**).

---

## 🏗️ Flagship Systems Engineering Portfolio

### 1. Bare-Metal Embedded Systems & Avionics

#### 🛸 [AeroCore-S3 Flight Controller Hardware & Firmware](https://github.com/yogesh031020/AeroCore-S3-Flight-Controller)
**Custom ESP32-S3 Flight Controller from schematic design to flight test.**
*   **Hardware Assembly & PCB Routing:** Designed the schematic, optimized high-speed routing to minimize EMI, managed power distribution regulators (BEC), and hand-soldered the dual-core core board. (Featured in [PCB Hardware Assembly Showcase](https://github.com/yogesh031020/Drone-PCB-Hardware-Assembly-Media-Showcase)).
*   **Low-Level Firmware:** Developed custom bare-metal C++ drivers for IMUs, gyroscopes, and barometers over SPI/I2C buses, implementing sensor calibration algorithms directly.

#### 📦 [Warehouse Drone v2.0: Companion Core & MAVLink Controller](https://github.com/yogesh031020/warehouse-drone-v2)
**Multitasking indoor package delivery UAV featuring external MAVLink overrides.**
*   **Companion Core Architecture:** Developed custom **ESP32 C++ firmware** running FreeRTOS tasks to parse and inject binary **MAVLink (Msg #70 RC Override)** packets into Pixhawk flight controllers via hardware UART.
*   **Sensor Bring-up:** Programmed downward **LiDAR** altitude locks, forward **ultrasonic** collision arrays, and **IR receiver arrays** using hardware interrupts for grid quadrant precision docking.
*   **Digital Twin (SITL):** Built a complete Software-in-the-Loop simulation validating takeoff, A* path navigation, package grasp, precision drop, and autonomous land states.

---

### 2. Distributed Robotics & ROS 2 Autonomy

#### 🌌 [Autonomous UAV Trinity Stack (Unified Autonomy Ecosystem)](https://github.com/yogesh031020/Autonomous-UAV-Trinity-Stack)
**Production-grade autonomous drone stack optimized for high-load reliability and failure-resilience.**
*   **Project AEGIS:** Designed a failure-resilient state machine monitoring battery/EKF variance, implementing automated recovery maneuvers (Emergency Hover/Limp Home) and writing high-frequency flight diagnostics to a local SQLite database.
*   **Project Swarm:** Established decentralized multi-agent coordination using **ROS 2 namespaces**, performing grid map merging from distributed SLAM Toolbox inputs.
*   **Project Zenith:** Engineered AI-driven reactive potential fields for dynamic obstacle avoidance utilizing YOLOv10 object detection.

#### 🔍 [Project CHRONOS: Infrastructure Inspection Stack](https://github.com/yogesh031020/Project-CHRONOS-Infrastructure-Inspection)
**Industrial structural inspector designed to operate safely inside GPS-denied environments.**
*   Integrated real-time **SLAM-based fallback** navigation loops to handle complete GNSS loss under bridges and towers.
*   Designed an automated Edge AI reporting engine classifying structural defects (rust, cracks, concrete decay).

---

### 3. Aerodynamics & Structural Analysis (Aerospace Physics)

#### 🦅 [Project ICARUS & Aero_VSP (CAD/FEA/CFD Architecture)](https://github.com/yogesh031020/Project-ICARUS)
**First-principles design and certification of High-Altitude Long-Endurance (HALE) wings.**
*   **Aerodynamic Optimization:** Modeled high-fidelity geometries in **OpenVSP** and validated Lift/Drag polars using **OpenFOAM (CFD)** simulations.
*   **Structural Certification:** Executed finite element analysis (**FEA in PrePoMax/CalculiX**) to verify structural integrity and wing shear stress limits under max load factors.

---

## 🛠️ Technology & Tools Matrix

---

## 📊 GitHub Contribution Metrics

<div align="center">
  <table border="0">
    <tr>
      <td width="50%" align="center">
        <img src="https://github-readme-stats.vercel.app/api?username=yogesh031020&show_icons=true&theme=dark&hide_border=true&count_private=true" alt="GitHub Stats" />
      </td>
      <td width="50%" align="center">
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=yogesh031020&layout=compact&theme=dark&hide_border=true" alt="Top Languages" />
      </td>
    </tr>
  </table>
</div>

---

## 💼 Industrial Experience (Novatech Robo Pvt Ltd)
*   **2+ Years UAV Operations:** Successfully conducted 150+ hours of commercial UAV operations (multirotors/fixed-wings) for mapping, agriculture, and industrial surveys.
*   **Avionics Calibration:** Tuned cascade PID control gains, calibrated high-end IMUs/compasses, and analyzed binary telemetry logs (APM/PX4) to trace sensor anomalies and flight deviations.

---

📫 **Get in Touch:**  
📬 **Email:** [yogeshes376@gmail.com](mailto:yogeshes376@gmail.com) | 🌐 **Web Portfolio:** [yogesh031020.github.io](https://yogesh031020.github.io/)  
📄 **License:** All flagship repository architectures are open-source and licensed under the **MIT License**.
