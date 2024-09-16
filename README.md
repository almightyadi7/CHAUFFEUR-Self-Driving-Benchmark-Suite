# CHAUFFEUR-Self-Driving-Benchmark-Suite
1. Developed CHAUFFEUR, an open-source benchmark suite for simulating self-driving vehicle systems, using Gazebo for sensor-based tasks like camera and LIDAR integration, focusing on resource-constrained, real-time embedded platforms like NVIDIA Jetson TX2 and Drive PX2.
2. Implemented YOLOv3 for object detection and tracking with an accuracy of 91%, along with Structure from Motion (SFM) for 3D reconstruction and lane detection through image processing techniques (perspective transform, curvature estimation).
3. Utilized Extended Kalman Filter (EKF) for improved vehicle localization, combining data from sensors like IMU, GPS, and LIDAR to handle drift and noise in the system’s position estimates.
4. Achieved efficient path planning using a Kalman filter-based SLAM algorithm and PID controllers for actuation, successfully navigating through the environment while avoiding obstacles in the simulated world.
