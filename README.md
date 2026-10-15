# 🚗 Autonomous Mobile Robot (AMR)

> Differential drive · DFRobot direct-drive hub motors · ROS 2 · SLAM

![Status](https://img.shields.io/badge/status-early%20build-orange)
![ROS](https://img.shields.io/badge/ROS-2-22314E)

<!-- TODO: chassis photo -> media/hero.jpg -->
<!-- TODO: motor bench-test clip -> media/motor-test.gif -->

## Overview

A two-wheel differential-drive mobile robot, built towards ROS 2 navigation and SLAM. The motor is bench-tested over UART from an ESP32-S3.

## Hardware

| Part | Detail |
|---|---|
| Drive | 2 × DFRobot direct-drive hub motors (M0603B) |
| Low-level control | ESP32-S3 (UART to motors) |
| Main compute | Jetson Orin Nano or Raspberry Pi 5 (+ Hailo) — being decided |
| Perception | RPLIDAR A1M8 or depth camera, plus an IMU |

<!-- TODO: planned architecture diagram -> media/architecture.png -->

## Roadmap

- [x] Motor bench test over UART
- [ ] Chassis and wiring
- [ ] ROS 2 base driver and odometry
- [ ] LIDAR SLAM mapping
- [ ] Nav2 autonomous navigation

## Author

**Jasin Jesin** · [LinkedIn](https://www.linkedin.com/in/jasinjesin/)
