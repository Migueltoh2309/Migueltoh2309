# Hi, I'm MiTo Olórtegui Huamán 👋

**Mechatronics engineer and master's student at UTEC** (Lima, Peru), working
on robotics: control systems, robotic manipulators, humanoids and autonomous
systems. I like taking an idea all the way from the math and the simulation to
the real hardware.

🔭 **Currently:** my master's thesis, *Development of a learning-from-demonstration
algorithm for robotic assistance in fruit picking on a conveyor belt using
computer vision and a humanoid robot*. I capture human demonstrations with
cameras and build the control, collision avoidance and vision a Unitree H1-2
humanoid needs to pick tangerines from a moving belt.

## 🤖 Projects

### Humanoid robotics (master's thesis)

| Project | What it does |
|---|---|
| [**H1_2_Humanoid_Control**](https://github.com/Migueltoh2309/H1_2_Humanoid_Control) | ROS 2 control stack for the Unitree H1-2: whole-body IK with joint limits, QP control, 3-layer bimanual collision avoidance (velocity dampers, arm coordination, RRT-Connect), RGB-D fruit localization and visual servoing, validated in MuJoCo and RViz2 |
| [**Multiview_Demo_Capture**](https://github.com/Migueltoh2309/Multiview_Demo_Capture) | Markerless capture of human arm motion with 3 calibrated RGB cameras (ChArUco, MediaPipe Pose, multi-view triangulation) to build a learning-from-demonstration dataset |

### Manipulators and mobile robots

| Project | What it does |
|---|---|
| [**UR5_ROS2_Algorithms**](https://github.com/Migueltoh2309/UR5_ROS2_Algorithms) | Kinematics and control for the UR5 arm in ROS 2: FK/IK, Jacobian control, QP, writing words with the end effector, and trajectories generated from natural language with a local LLM |
| [**SwarmBot_microROS**](https://github.com/Migueltoh2309/SwarmBot_microROS) | 🚧 Swarm of differential-drive robots on ESP32-S3 + micro-ROS talking to ROS 2 over Wi-Fi: IMU, wheel velocity control and automatic reconnection, plus URDF/RViz simulation |

### Embedded systems and control

| Project | What it does |
|---|---|
| [**Quadruped_Cat_Robot**](https://github.com/Migueltoh2309/Quadruped_Cat_Robot) | Cat-inspired quadruped: floating-base inverse kinematics simulated in MATLAB and running on an ESP32 with 8 servos, trot gait and Bluetooth commands |
| [**DC_Motor_Control**](https://github.com/Migueltoh2309/DC_Motor_Control) | DC motor with quadrature encoder: plant identification, PI velocity and PD position control on Arduino (current control and ESP32 port in progress) |

## 🛠️ Tools

**Languages:** Python · C++ · C · MATLAB

**Robotics:** ROS 2 Humble · MuJoCo · RViz2 · Gazebo · micro-ROS · inverse kinematics · QP control (OSQP) · motion planning

**Vision:** OpenCV · MediaPipe · YOLO · camera calibration · RGB-D (Intel RealSense)

**Embedded:** ESP32 / ESP32-S3 · ESP-IDF · FreeRTOS · Arduino

## 📫 Contact

✉️ [molortegui@utec.edu.pe](mailto:molortegui@utec.edu.pe)
