### Hi there, I'm ([@atlas-v](https://github.com)) 👋

**Robotics & Controls Engineer** at JR Automation, building machine vision systems and robotic cells for Fortune 500 manufacturers.<br />
Outside work I'm building **Sentinel**, an autonomous UGV, to go deeper on ROS 2, embedded firmware, and navigation.

**🏭 Professional (JR Automation)**
- Machine vision inspection, including 64MP micrometer-scale defect detection and 3D component registration
- New robotic cell development and pick-and-place sequencing (<1 defect per 300 cycles)
- PLC/HMI work, plus Python and Node.js tooling that talks to devices over TCP sockets

**🤖 Autonomous Systems & ROS 2: Sentinel UGV**

<img width="560" height="575" alt="Sentinel_Mission_Start" src="https://github.com/user-attachments/assets/a90c1986-3813-4649-a65f-36d643db338a" />
<img width="640" height="663" alt="Sentinel_Mission_Running" src="https://github.com/user-attachments/assets/864d963e-dead-4c25-b75d-e76a54ca812d" />

- **Architecture:** Raspberry Pi 5 running ROS 2 for autonomy, paired with a Pico 2W (RP2350) real-time motor/sensor controller on Zephyr RTOS
- **State estimation:** GPS / IMU / wheel-encoder integration feeding live robot pose
- **Control:** Kinematic vehicle modeling, closed-loop motor speed control, and pure pursuit / Stanley path tracking
- **Planning:** Valhalla road/path routing with Bézier curve smoothing for drivable paths
- **Autonomy:** ROS 2 mission coordinator node handling waypoint missions, live status publishing, and remote abort
- **Ground station:** React + MapLibre web UI with an offline tile server, a waypoint mission planner, and a live map of the robot and its active mission, all self-hosted in Docker

**🧪 Pulse Robotics** ([pulserobotics.com](https://pulserobotics.com))
- Personal hub for my robotics projects and side interests in financial modeling and web scraping
- Daily data pipeline that pulls market data for every available ticker into a self-hosted PostgreSQL database


**🌱 Currently learning:** Go, LiDAR/SLAM
 
🌐 [ryanbaumann.me](https://ryanbaumann.me) · 📫 rbaumann99@gmail.com

---

<p align="center"><b>Robotics, Embedded & Perception</b></p>
<p align="center">
  <a href="#">
    <img src="https://skillicons.dev/icons?i=cpp,python,ros,linux,raspberrypi,cmake,docker,git,opencv,autocad" />
  </a>
</p>

<p align="center"><b>Backend, Telemetry & Infrastructure</b></p>
<p align="center">
  <a href="#">
    <img src="https://skillicons.dev/icons?i=js,html,css,nodejs,go,react,vite,postgresql,docker,git" />
  </a>
</p>

---


### Skills
- **Robotics & Autonomy:** ROS 2 (nodes, topics, custom messages), mission planning, waypoint navigation, sensor integration (GPS, IMU, encoders)
- **Control & Planning:** Kinematic modeling, pure pursuit, Stanley controller, closed-loop motor speed control, Bézier path smoothing, Valhalla routing
- **Embedded:** Zephyr RTOS, C/C++, RP2040/RP2350, Raspberry Pi 5, UART/SPI/I2C
- **Machine Vision & Controls:** Basler, OpenCV, 2D/3D inspection, PLC programming, HMI design, AutoCAD Electrical
- **Software:** Python, JavaScript/Node.js, React, Vite, PostgreSQL, TCP/IP sockets, REST APIs, Linux, Docker, Git

