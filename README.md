# super-robot
    An autonomous navigation system for the Husky robot, built on ROS (Robot Operating System) and Gazebo. This project implements a wall-following algorithm to navigate unstructured environments by processing real-time LIDAR sensor data and incorporates real time pid tuning.

# 🛠 Key Features

## Wall-Following Logic
Implements a PID-based navigation controller that processes sensor_msgs/LaserScan to maintain a consistent distance from obstacles. Implemented in Python.

## Containerized Development:
Uses Docker to provide a reproducible, platform-independent simulation environment, ensuring consistent performance across macOS and Linux.

## Virtual Display Integration:
Integrated with VNC and X11 forwarding to allow GUI-based Gazebo and Rviz tools to run seamlessly from within the container.