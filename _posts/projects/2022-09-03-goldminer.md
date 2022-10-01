---
layout: project
permalink: /:title/
category: projects

meta:
  keywords: "Jekyll, Pineapple"

project:
  title: "GoldMiner"
  type: "Lab-Developed Mobile Robot with Manipulator"
  url: "https://github.com/RoboVigor/gold-miner-robot"
  logo: "/assets/images/projects/goldminer/cover.png"
  tech: "ROS, Linux, MoveIt, STM32, Docker"

agency:
  title: "RoboVigor Robotics Lab"
  url: "https://github.com/RoboVigor"
  year: "2021"

images:
  - image:
    url: "/assets/images/projects/goldminer/2022-10-01_00-49.png"
    alt: "exec"
  - image:
    url: "/assets/images/projects/goldminer/2022-10-01_00-49_1.png"
    alt: "robot"
---
- Detected bounding boxes of objects with CenterNet, then obtained 3D positions with depth images.
- Designed a Moveit controller with Gazebo simulation and a "pick and place" workflow.
- Implemented 200Hz host-client communication between Nvidia Jetson TX2 and STM32.
- Used an STM32 embedded system library CornerStone with RTOS to control the robot.