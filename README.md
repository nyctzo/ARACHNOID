ARACHNOID is a four-legged (quadruped) robot designed to maintain balance at any angle using real-time sensor feedback and closed-loop control.
The robot mimics spider-like motion and stability by continuously adjusting 12 servo motors based on data from an accelerometer + gyroscope (MPU6050).

This project combines robotics, embedded systems, control theory, and mechanical design, making it a complete end-to-end hardware + software system.

🧠 Key Features

🤖 Self-Balancing Quadruped

🎯 PID Control System for posture stabilization

🧭 MPU6050 IMU for real-time orientation (pitch & roll)

🦿 12 SG90 Servo Motors for precise leg articulation

📟 OLED Display for live sensor & status feedback

📡 Bluetooth Control for wireless interaction

🔋 Battery Management System (BMS) for safe power delivery

🧩 Modular & expandable architecture

🛠️ Hardware Stack
Component	Description
🧠 Arduino Nano	Main controller
📐 MPU6050	Accelerometer + Gyroscope
🦾 12× SG90 Servos	Leg movement & balancing
🔋 Li-ion Battery + BMS	Power & protection
📟 OLED Display (I2C)	Live diagnostics
📡 HC-05 Bluetooth	Wireless communication
🔌 Servo Expansion Board	Clean servo management
⚙️ How It Works (High Level)

IMU reads orientation (pitch & roll)

PID controller calculates error

Servo angles are adjusted dynamically

Robot corrects tilt and stabilizes itself

OLED shows real-time angles & system state

This loop runs continuously, allowing ARACHNOID to balance even when disturbed.

🧩 Project Structure
ARACHNOID/
│
├── src/                # Arduino source code
│   ├── pid_control/
│   ├── imu/
│   └── bluetooth/
│
├── data/               # Sensor logs & test data
│
├── models/             # CAD / STL files for 3D printing
│
├── images/             # Wiring diagrams, robot photos
│
├── videos/             # Assembly & working demos
│
├── docs/               # Build guides & documentation
│
└── README.md

🧪 What This Project Demonstrates

✔ Embedded programming
✔ Control systems (PID)
✔ Sensor fusion (IMU)
✔ Power management
✔ Hardware-software integration
✔ Robotics kinematics
✔ Real-world debugging

🎥 Demo & Assembly

📹 Assembly videos show step-by-step construction

📸 Images cover wiring, calibration & final build

📂 STL files included for 3D printing

All build details are documented inside the repository folders.

🎯 Future Improvements

🚶 Gait optimization (walk / trot / turn)

🤖 Autonomous navigation

📱 Mobile app control

🧠 Kalman / Complementary filter for IMU

🔊 Voice or gesture control

👨‍💻 About the Creator

Built as a hands-on robotics project to explore real-world control systems and intelligent motion.
This project reflects strong interest in robotics, AI-driven systems, and embedded engineering.
