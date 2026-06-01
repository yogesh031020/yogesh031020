# 🛸 YOGESH E S | UAV AUTONOMY & AVIONICS SYSTEMS ENGINEER

<div align="center">
  
  [![Portfolio Website](https://img.shields.io/badge/PORTFOLIO-yogesh031020.github.io-00E5FF?style=for-the-badge&logo=google-chrome&logoColor=black)](https://yogesh031020.github.io/)
  [![Email](https://img.shields.io/badge/EMAIL-yogeshes376%40gmail.com-BD00FF?style=for-the-badge&logo=gmail&logoColor=white)](mailto:yogeshes376@gmail.com)
  
  <br>

  `SYSTEM_STATUS: ACTIVE 🟢` | `TELEM_LOCK: 100% 📡` | `EKF3_STATE: OPTIMAL 🏆`
  
  <br>
  
  <img src="https://raw.githubusercontent.com/andryback/andryback/main/av.gif" width="60%" alt="Avionics Telemetry Visualizer" />

</div>

---

### 🧠 System Diagnostic & Core Bio
> **Aerospace Systems Engineer (B.E.)** specializing in bare-metal embedded C++ firmware, real-time control loops, and distributed robotic flight stacks (ROS 2). Formerly at **Novatech Robo Pvt Ltd**, managing real-world commercial flight operations, sensor calibrations, and black-box telemetry analysis. I build deterministic hardware-software ecosystems designed to operate under real-world physical constraints.

---

## ⚡ The Avionics System Stack

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h4>🔵 Low-Level Firmware & Control</h4>
      <ul>
        <li><code>C++ (11/14/17)</code> / Bare-Metal C</li>
        <li><code>ArduPilot (C++ core)</code> & <code>PX4 Autopilot</code></li>
        <li><code>FreeRTOS</code> Task Scheduling & Queues</li>
        <li><code>MAVLink Msg #70</code> Overrides & <code>uORB</code> Pub/Sub</li>
        <li>I2C, SPI, UART, DShot, PWM Actuators</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🟢 High-Level ROS 2 Autonomy</h4>
      <ul>
        <li><code>ROS 2 (Jazzy / Humble)</code> Core Nodes</li>
        <li>Extended Kalman Filter (<code>EKF3</code>) Fusion</li>
        <li>3D SLAM Toolbox & Distributed Map Merging</li>
        <li>Dynamic Obstacle Avoidance (YOLOv10 Edge AI)</li>
        <li>Custom <code>A* Pathfinding</code> Graph Solvers</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>🟣 Hardware & PCB Design</h4>
      <ul>
        <li><code>KiCad</code> Schematic Design & Routing</li>
        <li>High-Speed Telemetry & EMI Shielding</li>
        <li>Multi-layer Power Distribution (BEC)</li>
        <li>Hand-Soldering, Assembly & Stress Testing</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🟠 Aerospace Physics & Tools</h4>
      <ul>
        <li><code>OpenVSP</code> High-Fidelity CAD Geometry</li>
        <li><code>PrePoMax / CalculiX</code> Structural FEA</li>
        <li><code>OpenFOAM</code> Aerodynamic CFD</li>
        <li>Docker, Git CI/CD, Ubuntu Linux</li>
      </ul>
    </td>
  </tr>
</table>

---

## 🚀 Flagship Project Showrooms

> [!NOTE]
> ### 📦 01 / Warehouse Drone v2.0 — C++ Firmware & SITL Twin
> **Bare-Metal C++ Companion Core & Software-in-the-Loop Mission Control.**
> *   **Companion MCU:** Coded an ESP32-WROOM core running FreeRTOS tasks to inject high-frequency MAVLink RC overrides into Pixhawk.
> *   **Sensor Suite:** Programmed downward LiDAR altimeters, HC-SR04 sonar filters, and IR beacon interrupt arrays for precision coordinate docking.
> *   **Digital Twin:** Validated a full autonomous pickup-to-landing sequence inside an ArduPilot SITL environment.
> 
> 🔗 **Links:** [Access Repository](https://github.com/yogesh031020/warehouse-drone-v2) | [View SITL Simulation Run](https://github.com/yogesh031020/warehouse-drone-v2/raw/main/docs/warehouse_v2_simulation.mp4)

> [!TIP]
> ### 🌌 02 / Autonomous UAV Trinity Stack
> **Failure-Resilient distributed multi-agent swarm architecture in ROS 2.**
> *   **Project AEGIS:** Fail-safe state machine monitoring battery/EKF variance, writing telemetry data live to a SQLite black box.
> *   **Project Swarm:** Namespace-isolated decentralized map merging using SLAM Toolbox.
> *   **Project Zenith:** Jetson-level YOLOv10 object detection steering reactive potential field avoidance.
> 
> 🔗 **Links:** [Access Repository](https://github.com/yogesh031020/Autonomous-UAV-Trinity-Stack)

> [!IMPORTANT]
> ### 🛸 03 / AeroCore-S3 Flight Controller Hardware
> **Custom ESP32-S3 Autopilot Avionics board from schematic design to flight test.**
> *   **Hardware Design:** Designed multi-layer PCB in KiCad with isolated telemetry paths, noise-calibrated BEC rails, and low-latency IMU buses.
> *   **Firmware Board Support:** Authored bare-metal C++ drivers for on-board gyros and barometers over SPI.
> 
> 🔗 **Links:** [Access Repository](https://github.com/yogesh031020/AeroCore-S3-Flight-Controller) | [View PCB Showcase](https://github.com/yogesh031020/Drone-PCB-Hardware-Assembly-Media-Showcase)

> [!WARNING]
> ### 🦅 04 / Project ICARUS: Aerospace Certification
> **Physics-based design, structural FEA, and fluid aerodynamic analysis of a HALE Wing.**
> *   **Wing Design:** Evolved wing geometry programmatically inside OpenVSP using a Neural Network Optimizer.
> *   **Structural FEA:** Certified load limits and shear stress under high aerodynamic loads in PrePoMax.
> *   **Aerodynamic CFD:** Calculated lift-to-drag polar ratios using OpenFOAM mesh solvers.
> 
> 🔗 **Links:** [Access Repository](https://github.com/yogesh031020/Project-ICARUS)

---

## 📟 Live Mission Telemetry Log (Simulated)
```bash
[INIT] Initializing AeroCore-S3 Avionics Stack... OK
[SENSORS] IMU Calibrated | Baro Calibrated | EKF3 Filter Lock achieved
[TELEM] Connecting to GCS Companion Core via MAVLink... [CONNECTED]
[PREARM] Run failsafe diagnostic: Battery: 12.6V, GPS Sats: 18, Sensors: [SAFE]
[TAKEOFF] Setting Mode: GUIDED | Arming Motors | Commanding takeoff to 10.0m...
[NAV] Transitioning to Mode: AUTO | Uploading Waypoint grid map...
[NAV] Navigating to Waypoint 1 (PICKUP) | Distance: 25.4m | Cruise Alt: 10.0m
[PAYLOAD] Gripper status: CLOSING Servo... [PACKAGE SECURED]
[NAV] Navigating to Waypoint 2 (DELIVERY) | Distance: 48.2m
[PAYLOAD] Precision landing lock active | Descending to 1.50m... [PACKAGE RELEASED]
[NAV] Returning to Launch (RTL) | Alt: 10.0m
[LAND] Touchdown confirmed. Cutting motors. Disarming. [MISSION COMPLETE]
