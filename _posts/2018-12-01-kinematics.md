---
layout: post
title: "Kinematics Capstone"
description: "Serial Robotic Arm Control"
date: 2018-12-01
tags: HEBI Robot Controls
comments: false
photo_layout: "layout_2_pic_1"
photo1: "assets/Kinematics/frame_1.png"
photo2: "assets/Kinematics/robot_cropped.png"
---

This is my submission for the capstone project of the Robot Kinematics and Dynamics course at CMU. The goal of this project was to trace the end effector of a HEBI Robotics robot arm through an arbitrary track without tapping the edges.

All of the code for this project was written in MATLAB. In the spirit of the course, no external kinematics libraries were used. Gravity compensation, trajectory planning, and numerical IK were all implemented from scratch using first principles. To aid the development and testing of my solution, I also wrote some custom visualizations in MATLAB. I ended up having a competition-winning time of 7 seconds, adjusted to 9 seconds after edge-tapping penalties.

A video of my submission may be viewed below:
<iframe width="100%" height="auto" src="https://www.youtube.com/embed/BQ4f6Sq-F4I" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
