# 🚁 Drone Assembly Project

A hands-on exploration of quadcopter architecture and embedded systems. This project involved selecting components, understanding their roles, and assembling a basic drone platform for future robotics and autonomous navigation experiments.

---

## Components Used

### Frame

* F450 Quadcopter Frame
* Lightweight structure used to mount motors and electronics.

### Motors

* 4 × Brushless DC Motors (2212)
* Provide thrust required for flight.

### Electronic Speed Controllers (ESC)

* 4 × 30A ESCs
* Control the speed of each motor independently.

### Propellers

* 2 × Clockwise (CW)
* 2 × Counter-Clockwise (CCW)
* Generate lift and maintain stability.

### Flight Controller

* KK2 Flight Controller
* Responsible for stabilizing the drone and processing control inputs.

### Radio Transmitter

* FlySky FS-CT6B Transmitter

### Receiver

* FlySky Receiver Module
* Enables wireless communication between the transmitter and the drone.

### Battery Connector

* XT60 Connector
* Used to connect the power source.

### LiPo Battery

* High-discharge battery pack used to supply power to motors and electronics.

---

# Assembly Process

## Step 1: Frame Assembly

The four arms of the frame were attached to the center plate.

Purpose:

* Provide structural support.
* Maintain equal spacing between motors.

---

## Step 2: Motor Installation

Each brushless motor was mounted at the end of one arm.

Purpose:

* Generate thrust.
* Enable directional movement.

Motor configuration:

* Two clockwise motors.
* Two counter-clockwise motors.

---

## Step 3: ESC Connection

One ESC was connected to each motor.

Purpose:

* Convert battery power into controlled three-phase signals.
* Regulate motor speed.

---

## Step 4: Flight Controller Setup

The KK2 flight controller was mounted near the center of the frame.

Purpose:

* Maintain stability.
* Interpret control signals from the transmitter.
* Balance the drone during flight.

---

## Step 5: Receiver Integration

The FlySky receiver was connected to the flight controller.

Purpose:

* Receive commands from the remote controller.
* Transmit user inputs to the flight controller.

---

## Step 6: Propeller Installation

Propellers were mounted carefully.

Configuration:

* Front Left → Counter Clockwise
* Front Right → Clockwise
* Rear Left → Clockwise
* Rear Right → Counter Clockwise

⚠️ Incorrect propeller orientation can prevent takeoff.

---

## Step 7: Battery Connection

The LiPo battery was connected through the XT60 connector.

Purpose:

* Supply power to ESCs and electronics.

---

# System Architecture

```
FlySky Transmitter
        ↓
Receiver
        ↓
KK2 Flight Controller
        ↓
4 ESCs
        ↓
4 Brushless Motors
        ↓
Propellers
```

---

# Skills Learned

* Drone architecture fundamentals.
* Brushless motor operation.
* ESC functionality.
* Flight controller configuration.
* Power distribution concepts.
* Radio communication systems.
* Embedded systems and robotics fundamentals.

---

# Future Improvements

* GPS integration.
* Autonomous flight capabilities.
* Obstacle avoidance.
* Computer vision-based navigation.
* Integration with Raspberry Pi or Jetson Nano.
* ROS2 support.
* SLAM and path planning.

---

## Project Status

✅ Component selection completed

✅ Hardware assembly completed

🔄 Future upgrades planned for autonomous robotics experiments.
team Members
Arbind Malava
Parth
