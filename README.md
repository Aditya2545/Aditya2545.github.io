# Aditya Ghadshi — Robotics Software Engineer

**Live portfolio:** [aditya2545.github.io/portfolio](https://aditya2545.github.io/portfolio/)

Robotics Software Engineer specializing in **Visual SLAM, sensor fusion, and real-time perception**. Currently completing an M.S. in Computer Science at Texas A&M University–Kingsville, where I work as an Assistant Researcher at the AI-Cyb Lab on **collaborative multi-vehicle Visual SLAM for real-time Digital Twin synchronization** using a fleet of Quanser QCars.

📍 Austin, TX (open to relocation) · 📧 aditya.r.ghadshi@gmail.com · [LinkedIn](https://www.linkedin.com/in/aditya-r-ghadshi)

---

## Highlights

- ⚡ **32× inference speedup** on SuperPoint via TensorRT FP16 (14.66 ms → 0.45 ms, ~2,200 FPS on Tesla T4)
- 📉 **~76% odometry drift reduction** with a custom 5-state C++17 EKF sensor-fusion node
- 🚗 Multi-vehicle Visual SLAM pipeline on a Quanser QCar fleet with time-synchronized RGB-D streams
- 🤖 Nav2 + BehaviorTree.CPP v4 autonomy stack deployed on real TurtleBot3 hardware

## Featured Projects

| Project | Description | Stack |
|---|---|---|
| [ros2_ekf_fusion](https://github.com/Aditya2545/ros2_ekf_fusion) | 5-state Extended Kalman Filter fusing wheel odometry and IMU; ~76% drift reduction, gtest-covered | C++17, ROS 2, Eigen |
| [Camera–LiDAR Fusion & 3D MOT](https://github.com/Aditya2545) | 3D multi-object tracking pipeline on KITTI with camera–LiDAR fusion and Kalman-filter tracking | Python, OpenCV, KITTI |
| [qcar-digital-twin-sim](https://github.com/Aditya2545/qcar-digital-twin-sim) | Digital-twin simulator with neural map fusion, divergence detection, and pygame visualization (30 unit tests) | Python, pygame |
| [ros2_bt_navigation](https://github.com/Aditya2545/ros2_bt_navigation) | Behavior-tree autonomous navigation with Nav2, AMCL, and SLAM Toolbox; deployed on TurtleBot3 | ROS 2, BehaviorTree.CPP v4 |
| [ros2_camera_pipeline](https://github.com/Aditya2545/ros2_camera_pipeline) | Three-node camera driver and processing pipeline | ROS 2, V4L2, OpenCV |
| [warehouse_safety_monitor](https://github.com/Aditya2545/warehouse_safety_monitor) | Perception-based safety monitoring for warehouse robotics | Python, OpenCV |
| LIO-SAM on ROS 2 | Ported and ran LIO-SAM on ROS 2, resolving QoS, TF, and bag-conversion issues | ROS 2, LiDAR-inertial SLAM |

## Skills

**Languages:** C++17, Python
**Robotics:** ROS 2 / ROS, Nav2, BehaviorTree.CPP, SLAM Toolbox, AMCL, Gazebo, Isaac Sim
**Perception & SLAM:** Visual SLAM, SuperPoint, LIO-SAM, camera–LiDAR fusion, EKF / particle filters, 3D multi-object tracking
**Deployment:** TensorRT (FP16), ONNX, CUDA GPUs, real-time edge inference
**Data:** rosbag2, KITTI, EuRoC, `evo` benchmarking

## Certifications

Six Universal Robots Academy certifications (collaborative robot programming and deployment).

## About This Repo

This repository hosts my portfolio site via **GitHub Pages** (custom `index.html`, Jekyll `_config.yml` for SEO and sitemap generation).

```
portfolio/
├── index.html      # Portfolio site
├── _config.yml     # Jekyll / GitHub Pages configuration
└── assets/         # Images, CSS, JS
```

---

*Targeting research and engineering roles in perception, SLAM, and autonomy. Publication targets: IEEE ICRA, IROS, RA-L.*
