---
layout: project
permalink: /:title/
category: projects

meta:
  keywords: "Jekyll, Pineapple"

project:
  title: "EVCS"
  type: "Visual Checkout System for Cashierless Store"
  url: "https://github.com/jackweitze/ShoppingDetector"
  logo: "/assets/images/projects/autocashier/cover.png"
  tech: "Unreal Engine, YOLO"

agency:
  title: "Advised by Prof. Pei Zhang"
  url: "https://peizhang.engin.umich.edu/"
  year: "2022"

images:
  - image:
    url: "/assets/images/projects/autocashier/simulation.png"
    alt: "simulation"
  - image:
    url: "/assets/images/projects/autocashier/label.png"
    alt: "label"
  - image:
    url: "/assets/images/projects/autocashier/pipeline.png"
    alt: "pipeline"
  - image:
    url: "/assets/images/projects/autocashier/detection.png"
    alt: "detection on real world dataset"
---

- Built an Unreal Engine simulator of a real cashier-less store to generate datasets.
- Solved the problem of rare availability of public datasets and time-consuming real simulation.
- Used OpenPose to extract the positions of human hands and trained YOLO to identify products.
- Use background subtraction and feature tracking to get uncovered item image for classification.
- Explored problems like illumination changes, occlusion.
