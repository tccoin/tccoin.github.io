---
layout: project
permalink: /:title/
category: projects

meta:
  keywords: "Jekyll, Pineapple"

project:
  title: "CURLY SLAM"
  type: "Visual Object SLAM with FCOS network"
  url: "https://github.com/UMich-CURLY/curly_slam"
  logo: "/assets/images/projects/curlyslam/cover.png"
  tech: "C++, SLAM, Linux, ROS, OpenCV, GTSAM, Sophus, Docker"

agency:
  title: "Computational Autonomy and Robotics Laboratory<br>advised by Prof. Maani Ghaffari"
  url: "https://curly.engin.umich.edu/"
  year: "2022"

images:
  - image:
    url: "/assets/images/projects/curlyslam/2022-10-01_00-33.png"
    alt: "depth image"
  - image:
    url: "/assets/images/projects/curlyslam/2022-10-01_00-30.png"
    alt: "backend with loop closing"
  - image:
    url: "/assets/images/projects/curlyslam/2022-10-01_00-33_1.png"
    alt: "feature matching"
  - image:
    url: "/assets/images/projects/curlyslam/2022-10-01_00-33_2.png"
    alt: "feature tracking result"
---
- Built a SLAM system from scratch using ROS, including FCOS network for object detection, an OpenCV frontend, and a GTSAM backend with loop-closing.
- Trained FCOS network to extract object positions in the scene and further optimized in the backend.
- Improved feature matching to 300 matches per frame in frontend with correspondence search.
- Used factor graphs and GTSAM to optimize and fuse factors like SIFT/ORB features, IMU, and objects.
