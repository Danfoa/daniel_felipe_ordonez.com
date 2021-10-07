---
title: INVITE Robotics research platform
summary: ROS packages to simulate and operate all of INVITE's robotics hardware

tags:
  - Open Source
  - Robotics
date: "2019-01-31T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption:
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  name: code
  url: https://github.com/Danfoa/invite-robotics
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

After my internship at INVITE, during my last semester of the bachelor at the National University of Colombia, a team of engineers and me proposed to INVITE to tackle the problem of transitioning their research infrastructure to ROS, since their outdated industrial development environment lacked the flexibility to address complex automation tasks outside of the traditional automation applications.   

This project aimed to provide a comprehensive introduction to INVITE employees to the control of the company's hardware through ROS (Robot, 3D stereographic cameras, gripper, vacuum, and force sensors). We had to set up the entire research framework to combine existing developed ROS packages for their hardware and develop/extend several functionalities and packages. We decided to make part of the work public since, during development, we had to address several limitations on existing packages and develop tools that were not specific to INVITEs' goals. See more details on the repository documentation.

## Main Project Contributions
1. In order to operate the Motoman Dual-Arm CSD10F robot, we modified the MotoROS driver to enable the simultaneous planning and control of the different robot joint groups (torso, left arm, right arm), which at the time was not supported. (https://github.com/ros-industrial/motoman/pull/259)

2. Develop a simple cartesian task motion planner that enables automatic planning and control of the most common sequential motions the robots perform at INVITE (e.g., pick and place, apply tape to object, open bottle caps). We developed the feature before the MoveIt! task motion planner was published, but it shared most of its philosophy. (Users are encouraged to use MoveIt!'s version as it is far more flexible) (https://github.com/Danfoa/invite-robotics/blob/kinetic-devel/invite_utils/include/invite_utils/cartesian_task_planner.h)

![task_planning](https://user-images.githubusercontent.com/8356912/58956840-a936c700-879f-11e9-97ef-20062db53018.gif)


3. The development of a high-level control interface for the Robotiq grippers, enabling the hardware control through ROS action servers, the introduction of the gripper fingers as joints considered in the motion planning process, and the simulation of the robot grippers for off-line development. (https://github.com/Danfoa/robotiq_2finger_grippers)

4. Documentation and tutorial generation intended to ease the learning curve of the new robotics engineers joining INVITE GmbH (https://github.com/Danfoa/invite-robotics/wiki)

5. Configuration and sharing of the CSDA10F [URDF and Moveit Config files](https://github.com/ros-industrial/motoman_experimental/pull/43), along with the [Grippers, and sensors URDF and collision meshes](https://github.com/ros-industrial/robotiq/pull/138)

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=danfoa&repo=invite-robotics)](https://github.com/anuraghazra/github-readme-stats)
