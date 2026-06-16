---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **PhD / MASc, Mechanical and Mechatronics Engineering**, University of Waterloo, 2020-present
  * Research areas: autonomous driving, perception, motion planning, control, cooperative perception, and trustworthy mobility systems
  * Selected coursework: Adaptive Control, Introduction to Machine Learning, Optimal Control, Computer Vision, Autonomous Mobile Robotics
* **Bachelor of Engineering, Vehicle Engineering**, Beijing Institute of Technology, 2016-2020
  * Ranked 1st in class according to the CV record

Research experience
======
* **Autonomous vehicle motion planning**, University of Waterloo, 2020-2023
  * Developed point-cloud-based potential-field methods for autonomous vehicle motion planning.
  * Integrated motion planning with model predictive control while considering vehicle dynamics and passenger comfort.

* **All-weather perception and safe drivable space generation**, University of Waterloo, 2022-2024
  * Designed LiDAR-camera-HD map fusion methods for safe drivable space generation under adverse conditions.
  * Developed adaptive ground removal and noise-robust clustering approaches for autonomous driving perception.

* **Cooperative perception in indoor and infrastructure-assisted environments**, University of Waterloo, 2023-present
  * Developed delay-aware cooperative perception systems for intelligent mobility platforms.
  * Integrated infrastructure sensor data to improve real-time safety and responsiveness.

Project experience
======
* **WATonoBus: Waterloo All-Weather Autonomous Shuttle**, 2021-present
  * Contributed to perception, decision making, safety monitoring, motion planning, and control for a field-tested autonomous shuttle platform.
  * Supported autonomous shuttle demonstrations for industry and public-sector partners.

* **5G-Based Vehicle-to-Infrastructure (V2I) mobility system**, 2023-present
  * Developed a 5G-enabled vehicle-to-cloud system with solar-powered infrastructure sensor nodes.
  * Supported real-time sensor fusion, global planning, and remote management using edge computing and IoT capabilities.

Awards
======
* Velocity Up Start Award, 2025
* Mitacs Globalink Graduate Fellowship, 2020
* Outstanding Prize, RoboMaster 2020 AI Challenge (Perception), 2020
  
Skills
======
* **Programming:** Python, MATLAB/Simulink, C++
* **Robotics and perception:** ROS1/ROS2, OpenCV, LiDAR-camera calibration, multi-sensor fusion, autonomous driving perception
* **Machine learning:** PyTorch, TensorFlow, scikit-learn
* **Languages:** Chinese (native), English (fluent)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Service and leadership
======
* Organized and chaired the IEEE ITSC 2024 technical session "Trustworthy Diagnosis in Connected Mobility."
