---
layout: project
permalink: /:title/
category: projects

meta:
  keywords: "Jekyll, Pineapple"

project:
  title: "CURLY SLAM"
  type: "Visual-Inertial SLAM with GTSAM"
  url: "https://github.com/UMich-CURLY/curly_slam"
  logo: "/assets/images/projects/curlyslam/seasidetown.png"
  tech: "C++, SLAM, Linux, ROS, OpenCV, GTSAM, Sophus, Docker"

agency:
  title: "Computational Autonomy and Robotics Laboratory<br>Advised by Prof. Maani Ghaffari"
  url: "https://curly.engin.umich.edu/"
  year: "2022"

images:
  - image:
    url: "/assets/images/projects/curlyslam/seasidetown.png"
    alt: "backend result"
  - image:
    url: "/assets/images/projects/curlyslam/2022-10-01_00-33.png"
    alt: "depth image"
  - image:
    url: "/assets/images/projects/curlyslam/2022-10-01_00-33_1.png"
    alt: "feature matching"
  - image:
    url: "/assets/images/projects/curlyslam/2022-10-01_00-33_2.png"
    alt: "feature tracking result"
  - image:
    url: "/assets/images/projects/curlyslam/2022-10-01_00-30.png"
    alt: "backend with loop closing"
---
- Built a SLAM system from scratch using ROS, including an OpenCV frontend, and a GTSAM backend with loop-closing.
- Improved feature matching to $\sim{100}$ correct matches per frame in frontend with optical flow method and correspondence search.
- Evaluated with ground truth data in TartanAir dataset, 2% of matches are outliers.
- Used factor graphs and GTSAM to optimize and fuse factors like SIFT/ORB features, IMU, and objects.
- The backend achieves 3 times better ATE than the input odometry.