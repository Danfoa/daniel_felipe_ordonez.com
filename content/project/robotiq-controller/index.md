---
title: Robotiq 2-Finger Grippers Controller
summary: ROS package to control and simulate robotiq grippers series C
tags:
  - Open Source
  - Robotics
date: "2019-01-31T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption:
  focal_point: Center

links:
- icon: github
  icon_pack: fab
  name: code
  url: https://github.com/Danfoa/robotiq_2finger_grippers
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

This is a lightweight package that I designed during my time at INVITE GmbH for the control and simulation of the 2-finger Robotiq Grippers.

The package contains the necesary files to connect and control the Robotiq 2 finger adaptive grippers (85mm and 140mm stroke) of the C series through a **USB port using the Modbus RTU communication protocol**. The main contribution of this work are:

  - **Ease of control and programming**: We use ros `actionlib` Action Server/Clients to properly connect, control and command the grippers.
  - **State update and collision avoidance**: The driver updates the gripper joint position to `/joint_state` topic, enabling the planning of arm motions including finger motion with accurate collision avoidance. Additionally, this package provides collision meshes as simplified convex hulls of the visual meshes for both 85mm and 140mm stroke grippers.
  - **Simulation of grippers operation**. Previous control packages require an active connection to a real gripper to function, limiting off-line development.
  - Helper functions and examples for python and C++.

  Note: This package is based on [waypointrobotics/robotiq_85_gripper](https://github.com/waypointrobotics/robotiq_85_gripper) and [ros-industrial/robotiq](https://github.com/ros-industrial/robotiq), with many code changes and feature inclusions.

For further details see the [repository](https://github.com/Danfoa/robotiq_2finger_grippers)

  [![gripper operation](https://user-images.githubusercontent.com/8356912/52121064-a0ca5600-261e-11e9-8ad1-6b2855f11909.gif)](https://github.com/Danfoa/robotiq_2finger_grippers)

  [![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=danfoa&repo=robotiq_2finger_grippers)](https://github.com/anuraghazra/github-readme-stats)
