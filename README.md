# 🤖 RoboPilot V50 — AI Robotics Simulation Lab

RoboPilot V50 is a professional Python-based robotics simulation project designed to demonstrate core concepts of autonomous robotics, navigation, path planning, virtual sensors, obstacle avoidance, and robot control — all without requiring physical robot hardware.

## 🚀 Key Features

* 🤖 2D mobile robot simulation
* 🧠 A* pathfinding algorithm
* 🗺️ Interactive grid-based environment
* 📍 Start and destination points
* 🚧 Dynamic obstacle environment
* 📡 Virtual distance sensors
* 🧭 Automatic direction control
* 🤖 Autonomous navigation mode
* 🎮 Manual keyboard/GUI controls
* 🔋 Virtual battery monitoring
* 📏 Distance tracking
* 💥 Collision counter
* 📊 Live robot telemetry
* ⚡ Adjustable robot speed
* 🔄 Robot reset system
* 🎲 Random map generator
* 💾 JSON map saving
* 📂 JSON map loading
* 📝 Real-time event log
* 👁️ Sensor visualization
* 🛣️ Calculated path visualization
* 🎯 Automatic goal detection
* 🖥️ Interactive Tkinter GUI
* 📈 Live dashboard
* 🔌 Zero external API requirement
* 📦 Single-file architecture
* 🐍 Pure Python implementation

## 🧠 Robotics Concepts Demonstrated

RoboPilot V50 provides a practical introduction to important robotics concepts including:

* Robot motion
* Grid navigation
* Path planning
* Autonomous decision making
* Obstacle detection
* Sensor simulation
* Direction control
* Navigation algorithms
* Robot telemetry
* Battery simulation
* Collision handling
* Environment mapping

## 🗺️ A* Navigation

The simulator uses the A* algorithm to calculate a path from the robot's current position to the target. When obstacles are present, the navigation system searches for an alternative valid route.

The robot can continuously recalculate its route while navigating toward the destination.

## 📡 Virtual Sensors

RoboPilot includes simulated distance sensors that provide information about obstacles around the robot.

The dashboard displays:

* Front distance
* Left distance
* Right distance

This allows beginners to understand how sensor data can be used for autonomous robot navigation.

## 🎮 Control Modes

### Autonomous Mode

The robot automatically calculates a route and moves toward the target.

### Manual Mode

Control the robot using:

* ▲ Up
* ▼ Down
* ◀ Left
* ▶ Right

Keyboard arrow keys are also supported.

## 📊 Live Dashboard

The GUI continuously displays:

* Current position
* Robot direction
* Operating mode
* Speed
* Battery percentage
* Distance traveled
* Collision count
* Runtime
* Sensor readings
* A* path information
* Target coordinates

## 💾 Map System

Users can create and experiment with different environments.

Maps can be:

* Generated randomly
* Saved as JSON
* Loaded from JSON
* Reused for navigation experiments

## 🛠️ Technology Stack

* Python
* Tkinter
* A* Algorithm
* JSON
* Object-oriented programming
* Event-driven GUI
* Robotics simulation concepts

## 📦 Requirements

No external Python packages are required for the basic version.

The project uses Python's built-in modules, making it easy to run in:

* VS Code
* Windows Terminal
* Python IDLE
* Command Prompt

## ▶️ Run

```bash
python RoboPilot_V50.py
```

For Python 3.13:

```bash
py -3.13 RoboPilot_V50.py
```

## 🎓 Learning Applications

RoboPilot V50 can be used as a learning project for:

* Robotics students
* AI beginners
* Python learners
* Intelligent Systems students
* Autonomous navigation studies
* Algorithm practice
* Computer science projects
* University demonstrations

## 🔮 Future Expansion

The simulator can later be extended toward real robotics by connecting the software concepts with:

* Arduino
* ESP32
* Ultrasonic sensors
* IR sensors
* Servo motors
* DC motors
* Motor drivers
* Raspberry Pi
* Real robot chassis
* Camera-based vision
* OpenCV
* ROS 2

## 🚀 Project Call to Action

**Clone it, run it, experiment with the maps, modify the navigation logic, and build your own autonomous robot simulation. 🤖**

Turn your Python knowledge into practical robotics skills with **RoboPilot V50** — and take the next step from virtual simulation toward real-world robotics!
