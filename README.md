# Integrated Multi Load Handler (IMLH) - Pick-and-Place Wheeled Robot

This project presents the URDF model of a **Pick-and-Place Robot** integrated with a **wheeled mobile base**, designed as part of the **IMLH (Integrated Multi Load Handler)** system. The robot is modeled and launched in **ROS2**, allowing simulation and visualization in RViz.

---

## 🚀 Features

- ✅ Wheeled mobile robot platform
- ✅ Integrated robotic arm for pick-and-place tasks
- ✅ Modeled in URDF (Unified Robot Description Format)
- ✅ Launchable in RViz via ROS2
- ✅ Modular structure for extension and upgrades

---

## 📁 Project Structure

PickAndPlace-WheeledRobot-URDF/
├── urdf/
│   ├── pick_and_place_robot.xacro
│   ├── pick_and_place_robot.urdf
│   └── meshes/
│       └── [robot part meshes - STL/DAE files]
├── launch/
│   └── display.launch.py
├── rviz/
│   └── config.rviz
├── package.xml
├── CMakeLists.txt
├── LICENSE
└── README.md


## 🧠 Technologies Used

- **ROS2 (Robot Operating System)**
- **URDF/Xacro**
- **RViz for visualization**
- **Linux (Ubuntu recommended)**

---

## 📦 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/IMLH-Pick-and-Place.git

## 🧠 How to Use

 **Source your ROS2 workspace:**
   ```bash
   source /opt/ros/humble/setup.bash

