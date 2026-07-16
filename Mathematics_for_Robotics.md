# 🤖 Mathematics & Formula Reference for Robotics

A quick reference guide containing the mathematical concepts, equations, and performance metrics commonly used in robotics, autonomous systems, drones, computer vision, SLAM, and control systems.

---

# Table of Contents

- Basic Mathematics
- Trigonometry
- Linear Algebra
- Geometry
- Kinematics
- Dynamics
- Control Systems
- Drone Mathematics
- Coordinate Transformations
- Probability
- Optimization
- Computer Vision
- Path Planning
- Performance Metrics

---

# 1. Basic Mathematics

## Distance

\[
d=\sqrt{(x_2-x_1)^2+(y_2-y_1)^2}
\]

---

## Midpoint

\[
M=\left(\frac{x_1+x_2}{2},\frac{y_1+y_2}{2}\right)
\]

---

## Slope

\[
m=\frac{y_2-y_1}{x_2-x_1}
\]

---

# 2. Trigonometry

## SOH CAH TOA

\[
\sin\theta=\frac{Opposite}{Hypotenuse}
\]

\[
\cos\theta=\frac{Adjacent}{Hypotenuse}
\]

\[
\tan\theta=\frac{Opposite}{Adjacent}
\]

---

## Degree ↔ Radian

\[
Radians=Degrees\times\frac{\pi}{180}
\]

\[
Degrees=Radians\times\frac{180}{\pi}
\]

---

# 3. Vector Mathematics

## Magnitude

\[
||v||=\sqrt{x^2+y^2+z^2}
\]

---

## Dot Product

\[
A\cdot B=|A||B|\cos\theta
\]

Applications

- Object alignment
- Angle calculation
- Motion planning

---

## Cross Product

\[
A\times B
\]

Applications

- Rotation axis
- Torque
- Angular motion

---

# 4. Linear Algebra

## Matrix Multiplication

\[
C=A\times B
\]

Used in

- Robot transformations
- Camera projection
- SLAM

---

## Identity Matrix

\[
I=
\begin{bmatrix}
1&0&0\\
0&1&0\\
0&0&1
\end{bmatrix}
\]

---

## Matrix Transpose

\[
A^T
\]

---

## Matrix Inverse

\[
A^{-1}
\]

Used for coordinate transformations.

---

# 5. Coordinate Systems

## 2D Rotation Matrix

\[
R=
\begin{bmatrix}
\cos\theta & -\sin\theta\\
\sin\theta & \cos\theta
\end{bmatrix}
\]

---

## 3D Rotation

Rotation around

- X-axis
- Y-axis
- Z-axis

Commonly represented using

- Rotation Matrix
- Euler Angles
- Quaternion

---

# 6. Robot Kinematics

## Velocity

\[
v=\frac{d}{t}
\]

---

## Acceleration

\[
a=\frac{\Delta v}{t}
\]

---

## Angular Velocity

\[
\omega=\frac{\theta}{t}
\]

---

## Angular Acceleration

\[
\alpha=\frac{\Delta\omega}{t}
\]

---

# 7. Newtonian Dynamics

## Force

\[
F=ma
\]

---

## Momentum

\[
P=mv
\]

---

## Torque

\[
\tau=r\times F
\]

---

## Work

\[
W=Fd
\]

---

## Power

\[
P=\frac{W}{t}
\]

---

# 8. Drone Mathematics

## Total Thrust

\[
T=T_1+T_2+T_3+T_4
\]

---

## Hover Condition

\[
T=mg
\]

---

## Lift Force

Depends on

- Propeller RPM
- Air Density
- Blade Pitch

---

## Roll

Rotation around X-axis

---

## Pitch

Rotation around Y-axis

---

## Yaw

Rotation around Z-axis

---

# 9. PID Controller

## Control Equation

\[
u(t)=K_pe(t)+K_i\int e(t)dt+K_d\frac{de}{dt}
\]

Where

- P → Present Error
- I → Past Error
- D → Future Trend

---

# 10. State Estimation

## Kalman Filter

Prediction

\[
x'=Ax+Bu
\]

Correction

\[
K=P(H^TPH+R)^{-1}
\]

Used for

- Sensor Fusion
- GPS
- IMU
- Drone Localization

---

# 11. Probability

## Mean

\[
\mu=\frac{\sum x}{n}
\]

---

## Variance

\[
\sigma^2=\frac{\sum(x-\mu)^2}{n}
\]

---

## Standard Deviation

\[
\sigma=\sqrt{\sigma^2}
\]

---

# 12. Path Planning

Algorithms

- A*
- Dijkstra
- RRT
- RRT*
- PRM
- DWA

Cost Function

\[
f(n)=g(n)+h(n)
\]

---

# 13. Computer Vision

## IoU (Intersection over Union)

\[
IoU=\frac{Area_{Overlap}}{Area_{Union}}
\]

---

## Precision

\[
Precision=\frac{TP}{TP+FP}
\]

---

## Recall

\[
Recall=\frac{TP}{TP+FN}
\]

---

## F1 Score

\[
F1=\frac{2PR}{P+R}
\]

---

# 14. Robotics Performance Metrics

## RMSE

\[
RMSE=\sqrt{\frac{\sum(y-\hat y)^2}{n}}
\]

---

## MAE

\[
MAE=\frac{\sum |y-\hat y|}{n}
\]

---

## Accuracy

\[
Accuracy=\frac{Correct}{Total}
\]

---

## Latency

Time taken for the robot to react.

---

## FPS

Frames processed per second.

---

## Path Length

Total distance traveled.

---

## Battery Efficiency

Distance per unit energy consumed.

---

# 15. Common Robotics Coordinate Frames

- World Frame
- Map Frame
- Odom Frame
- Base Link
- Camera Frame
- IMU Frame
- GPS Frame
- Laser Frame

---

# 16. Essential Robotics Algorithms

- PID Controller
- Kalman Filter
- Extended Kalman Filter
- Particle Filter
- SLAM
- ICP
- ORB-SLAM
- Visual Odometry
- A*
- Dijkstra
- RRT
- RRT*
- MPC

---

# 17. SI Units

| Quantity | Unit |
|-----------|------|
| Distance | meter (m) |
| Time | second (s) |
| Velocity | m/s |
| Acceleration | m/s² |
| Force | Newton (N) |
| Torque | Nm |
| Power | Watt (W) |
| Voltage | Volt (V) |
| Current | Ampere (A) |
| Frequency | Hertz (Hz) |
| Mass | Kilogram (kg) |

---

# 📚 Recommended Topics to Learn

- Linear Algebra
- Calculus
- Differential Equations
- Probability
- Statistics
- Optimization
- Graph Theory
- Numerical Methods
- Control Theory
- State Estimation
- Computer Vision Mathematics
- Robotics Kinematics
- Dynamics
- Sensor Fusion

---

## References

- ROS 2 Documentation
- PX4 Documentation
- Gazebo Documentation
- OpenCV Documentation
- Eigen Library
- Modern Robotics (Northwestern University)
- Probabilistic Robotics
- Introduction to Autonomous Robots
