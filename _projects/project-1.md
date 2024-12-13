---
title: "AIRBUD"
excerpt: "A Drone for Autonomous Operations
---

This project involves the development of a fully autonomous, custom built drone capable of navigating and completing objectives based on object detection input. 

By integrating diverse systems such as the CubeOrange+ with PX4 autopilot and the ZED X Mini camera into the Jetson Orin NX, the drone leverages edge computing capabilities for real-time decision making, facilitated by ROS2. Custom ROS2 nodes were created to utilize CUDA-accelerated software and cuDNN for GPU-accelerated object detection, ensuring rapid and accurate responses. 

Currently, the team is training a system to track and follow other drones, addressing the need for advanced drone mitigation techniques. Future work aims to enhance adaptability and autonomy by training the drone with reinforcement learning techniques. Such tecniques would enable it to make dynamic decisions and navigate complex 3D environments in real-time based on object detection feedback.