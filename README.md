# Autonomous Robot Simulation
An autonomous navigation system for a Husky UGV, built on ROS (Robot Operating System) using the publisher-subscriber model and tested with world models using Gazebo. This project implements a wall-following algorithm to navigate unstructured environments by processing real-time LIDAR sensor data and incorporates the ability for real-time PID tuning.

## 🛠 Key Features

### Wall-Following Logic
Implements a PID-based navigation controller that processes sensor_msgs/LaserScan to maintain a consistent distance from obstacles. Implemented in Python.

### Containerized Development:
Uses Docker to provide a reproducible, platform-independent simulation environment, ensuring consistent performance across macOS and Linux.

### Virtual Display Integration:
Integrated with VNC and X11 forwarding to allow GUI-based Gazebo and Rviz tools to run seamlessly from within the container.
