# Suraya USV – Autonomous Surface Navigation

**Suraya USV** is an autonomous surface vehicle platform developed for real-time perception, navigation, and obstacle avoidance in maritime environments. It integrates stereo vision, LiDAR, GPS, and IMU for robust environmental situational awareness and autonomous control.

> ⚠️ This repository is a high-level documentation of the project. Due to government and research constraints, source code and deployment modules cannot be made publicly available.

---

## 🧠 Project Overview

- **Mission**: Enable real-time autonomous navigation for inland/coastal USV operations
- **Core Components**: Stereo camera, LiDAR, RTK-GPS, IMU, Jetson Nano
- **Software Stack**: ROS, MOOS-IvP, C++, Python

The system employs multi-sensor fusion for dynamic obstacle detection and navigation using a custom ESA (Environmental Situational Awareness) layer. It was tested in real-world deployments in both simulation and physical river environments.

---

## 📘 Related Publications

- **[An ESA-Based Perception System for Autonomous Surface Navigation](https://ieeexplore.ieee.org/document/10969632)**  
  *IEEE ICIT 2024*  
  Focused on ESA layer design and real-time obstacle avoidance using multi-sensor data.

- **[Integration of Stereo Vision and MOOS-IvP for Enhanced Obstacle Detection and Navigation in Unmanned Surface Vehicles](https://ieeexplore.ieee.org/document/10314528)**  
  *IEEE SysCon 2023*  
  Demonstrated the system’s real-time behavior integration using stereo vision and MOOS-IvP.

---

## 🎬 Project Demonstration Videos

1. **Navigation & Obstacle Avoidance Demo**  
   [![Watch Video](https://img.shields.io/badge/Watch-Video-blue)](https://drive.google.com/file/d/17rrR1ReYEjEEKBn0R51izWoNFJpeQzj9/view?usp=sharing)

2. **Autonomous Behavior Execution – River Test**  
   [![Watch Video](https://img.shields.io/badge/Watch-Video-blue)](https://drive.google.com/file/d/1tqD_GHLpesbP-rrXz5ujVgkOB_tPRv7u/view?usp=sharing)

---

## 📂 Repository Structure

