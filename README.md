# 🚁 Drone Development & Autonomous Systems

A comprehensive robotics project documenting the journey from building a physical quadcopter to developing autonomous drone systems using ROS 2, PX4, Gazebo, and modern robotics software.

This repository serves as both a hardware and software learning platform, covering drone assembly, simulation, flight control, autonomous navigation, and future AI-based capabilities.

---

# 📌 Project Goals

This project aims to understand every major component involved in autonomous drone development, including:

- Drone hardware assembly
- Flight controller integration
- PX4 Autopilot
- ROS 2 development
- Gazebo simulation
- MAVLink communication
- Autonomous flight
- Computer vision
- Navigation and path planning

---

# 🏗️ Project Structure

```
Drone Project
│
├── Hardware Assembly
│   ├── Frame
│   ├── Motors
│   ├── ESCs
│   ├── Flight Controller
│   ├── Radio System
│   └── Power Distribution
│
├── Drone Simulation
│   ├── PX4 Autopilot
│   ├── Gazebo Harmonic
│   ├── QGroundControl
│   ├── MAVLink
│   └── SITL Simulation
│
├── ROS 2 Development
│   ├── ROS 2 Humble
│   ├── Topics
│   ├── Nodes
│   ├── Services
│   ├── Launch Files
│   └── Offboard Control
│
├── Autonomous Navigation (Upcoming)
│
├── Computer Vision (Upcoming)
│
└── AI Applications (Upcoming)
```

---

# 🔧 Hardware Components

## Frame

- F450 Quadcopter Frame

## Motors

- 4 × 2212 Brushless Motors

## ESCs

- 4 × 30A Electronic Speed Controllers

## Propellers

- 2 × Clockwise
- 2 × Counter Clockwise

## Flight Controller

- KK2 Flight Controller

## Radio System

- FlySky FS-CT6B Transmitter
- FlySky Receiver

## Power System

- LiPo Battery
- XT60 Connector

---

# 🛠️ Hardware Assembly

The hardware section covers:

- Frame Assembly
- Motor Installation
- ESC Wiring
- Flight Controller Installation
- Receiver Integration
- Power Distribution
- Propeller Configuration

---

# 💻 Drone Simulation

A complete software simulation environment has been built using:

- ROS 2 Humble
- PX4 Autopilot
- Gazebo Harmonic
- QGroundControl
- MAVLink
- Ubuntu 22.04 (WSL2)

Current capabilities include:

- PX4 SITL Simulation
- Gazebo Drone Simulation
- MAVLink Communication
- Ground Control Station Integration
- ROS 2 Development Environment

---

# 🤖 ROS 2 Development

This repository will continue to grow with ROS 2 based drone applications, including:

- ROS 2 Nodes
- Publishers & Subscribers
- Services
- Actions
- Launch Files
- Parameter Handling
- Drone Teleoperation
- Offboard Control
- Sensor Integration

---

# 📡 Software Architecture

```
QGroundControl
        │
        ▼
     MAVLink
        │
        ▼
PX4 Autopilot (SITL)
        │
        ▼
Gazebo Harmonic
        │
        ▼
ROS 2
        │
        ▼
Custom Drone Applications
```

---

# 🚀 Technologies Used

## Robotics

- ROS 2 Humble
- PX4 Autopilot
- Gazebo Harmonic
- MAVLink
- QGroundControl

## Programming

- C++
- Python
- Bash

## Operating System

- Ubuntu 22.04 (WSL2)

## Version Control

- Git
- GitHub

---

# 📚 Learning Objectives

This repository documents practical learning in:

- Drone Architecture
- Flight Dynamics
- Embedded Systems
- Flight Controllers
- Autonomous Robotics
- Drone Simulation
- Robot Operating System (ROS 2)
- MAVLink Communication
- Drone Navigation
- Robotics Software Development

---

# 🔮 Future Roadmap

## Simulation

- [x] PX4 SITL
- [x] Gazebo Harmonic
- [x] QGroundControl
- [ ] Multi-drone simulation
- [ ] Custom drone models

## ROS 2

- [ ] Keyboard Teleoperation
- [ ] Joystick Teleoperation
- [ ] Offboard Control
- [ ] Sensor Integration
- [ ] Mission Planning

## Computer Vision

- [ ] OpenCV Integration
- [ ] Object Detection
- [ ] Obstacle Avoidance
- [ ] Visual Navigation

## Autonomous Flight

- [ ] GPS Navigation
- [ ] Waypoint Missions
- [ ] SLAM
- [ ] Path Planning
- [ ] AI-assisted Navigation

---

# 📈 Current Status

## Hardware

- ✅ Drone Components Selected
- ✅ Drone Assembly Completed

## Software

- ✅ ROS 2 Installed
- ✅ PX4 Installed
- ✅ Gazebo Harmonic Configured
- ✅ QGroundControl Connected
- ✅ PX4 SITL Running
- ✅ Drone Simulation Operational

## In Progress

- 🔄 ROS 2 Drone Control
- 🔄 Offboard Flight Control
- 🔄 Autonomous Navigation

---

# 👥 Team

- **Arbind**
- **Parth**

---

## ⭐ Project Vision

This repository is intended to evolve into a complete open-source learning resource covering the full development pipeline of autonomous drones—from hardware assembly to intelligent autonomous flight using ROS 2, PX4, computer vision, and AI.
