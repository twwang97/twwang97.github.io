---
layout: archive
title: "David's Resume"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}


[Download my resume here.](http://twwang97.github.io/files/resume_TsungWun.pdf)

Education
======
* M.S. in Mechanical Engineering, National Taiwan University, 2023
  * Thesis: [Development of 3D Reconstruction and Navigation for Mobile Robots](https://twwang97.github.io/thesis/) (DOI: 10.6342/NTU202303775)
  * Relevant Coursework: Advanced Computer Vision, 3D Computer Vision with Deep Learning Applications, Operating Systems, Adaptive Signal Processing, System Identification
* B.S. in Mechanical Engineering, National Taiwan University, 2020
  * Relevant Coursework: Robot Vision, Introduction to Robotics, Machine Learning

Work experience
======
* <b>Engineer</b> at [Vecow Co., Ltd.](https://www.vecow.com/) (Oct. 2023 – Sept. 2025)
  * Architected FPGA + Vitis pipeline on Zynq UltraScale+ MPSoC for deterministic multi‑camera streaming.
  * Ported ROS2 Humble EKF localization and gPTP time sync into PetaLinux using a meta‑ros layer.
  * Developed sensor fusion (IMU + GPS) to improve AMR navigation accuracy.
  * Implemented Python test automation to reduce regression time and accelerate releases.
  * Configured device tree bindings and produced Debian 11 builds for rapid, standardized deployment.

* <b>Firmware Engineering Intern</b> at [Aeroprobing Inc.](https://aeroprobing.com/) (Jun. 2021 – Aug. 2022)
  * Developed and optimized FreeRTOS-based task synchronization for drones.
  * Managed sensor modules with SPI/I2C/UART protocols.
  * Applied the extended Kalman filter to enhance orientation, altitude, and position estimation.
  * Fine-tuned drone controls using PID control in cascade loops, improving flight stability.

* <b>Mechanical Engineering Intern</b> at [Symbio, Inc.](https://www.symbioinc.com.tw/zh-tw) (Jul. 2018 – Aug. 2018)
  * Innovated tools to enhance coating efficiency and product quality.
  * Collaborated with a team of eight to maintain and optimize the manufacturing process.

* <b>Software Developer</b> in [Hello RoBi1.0 Robotic Startup Bootcamp](https://starrocket.io/) (Dec. 2017 – May 2018)
  * Embedded a recommender system in Pepper Robot for product promotion in furniture stores.
  * Enhanced brand experience through integrated online and offline marketing strategies.


Course projects
======
* <b>Analysis of 4-bit Counter using J-K Flip-Flops with LTspice, ModelSim, and DE2-115</b> (Fall 2025) [GitHub](https://github.com/twwang97/altera-de2-115.git), [Report](http://twwang97.github.io/files/report_fpga_4bit_counter.pdf), [YouTube](https://youtu.be/KPDtDhJqPgE)
  * Designed a 4-bit counter using J-K FFs in LTspice with an R-2R D/A converter and ran simulation.
  * Implemented a 4-bit counter in VHDL, synthesized with Quartus, and verified such a design using ModelSim testbenches.
  * Developed a two-stage synchronizer to debounce the pushbutton and demonstrated real‑time operation with 7‑segment display on DE2-115.

* <b>Real-time Pipeline for 3D Mesh Reconstruction from RGB-D Data</b> (Spring 2023) [YouTube](https://youtu.be/tccfjy2j27w)
  * Developed a real-time pipeline for 3D mesh reconstruction using RGB-D data.
  * Enhanced camera pose estimation accuracy with bilateral filtering.
  * Implemented GPU acceleration, achieving real-time performance for large-scale environments.

* <b>SAD-SLAM</b> (Fall 2022) [Github](https://github.com/MartyJan/SAD-SLAM) 
  * Enhanced the NICE-SLAM algorithm with Sign-Agnostic optimization.
  * Integrated Mask-RCNN to handle dynamic obstacles in SLAM structure.
  * Validated the approach using a handheld RealSense camera.

* <b>MIMO System Identification of A Quadcopter</b> (Spring 2022) [report](http://twwang97.github.io/files/report_sysID_David.pdf) [video](https://youtube.com/shorts/HsXJFUH4R2Q)
  * Conducted MIMO system identification on a quadcopter, comparing various models.
  * Designed and tested a robust controller, evaluating performance improvements.

Courses & Certifications
======
Here are some of the training courses I've completed recently, including details on the course content and certificates.

* <b>The Electronics and AI Training Program</b> (National Yang Ming Chiao Tung University) [Certificate](http://twwang97.github.io/files/certificate_nycu_fall2025.jpg) 
  * Completed on Nov. 2025  
  * Course Contents:
    - Electronic Circuit Design (40 hr)
    - Digital Design with FPGA (50 hr)
    - Semiconductor Manufacturing Technology (30 hr)
    - Introduction to Semiconductor Equipment (AOI Focus) (20 hr)
    - CMOS Memory Circuits (12 hr)
    - Microelectronics Labs (12 hr)
    - Data Analysis with Python (40 hr)

* <b>Introduction to Semiconductor and MEMS Fabrication</b> (Coursera) [Certificate](https://www.coursera.org/account/accomplishments/specialization/X6IEHL9THGNY)
  * Completed on Oct. 2025
  * Course Contents:
    - Introduction to Microfabrication
    - Microfabrication Fundamental Processes
    - Additional Process Techniques in Microfabrication
    - Introduction to Micro Electro Mechanical Systems (MEMS)
    - Modeling, IC Processes and Emerging Microtechnology

* <b>Semiconductor Characterization</b> (Coursera) [Certificate](https://www.coursera.org/account/accomplishments/specialization/EVY9BF4NVJP5)
  * Completed on Oct. 2025
  * Course Contents:
    - Fundamentals of Semiconductor Characterization
    - Electrical Characterization: Diodes
    - Electrical Characterization: MOSFETs
    - Electron and Ion Beam Characterization
    - Optical and X-Ray Characterization

* <b>VLSI CAD Part I: Logic</b> (Coursera) [Certificate](https://www.coursera.org/account/accomplishments/verify/IITCCWT542BK)  
  * Completed on Oct. 2024  
  * Learned logic synthesis, Boolean representations, and CAD algorithms for optimizing digital circuits

* <b>FPGA Computing Systems</b> (Coursera) [Certificate](http://twwang97.github.io/files/Coursera_FPGAcomputingSpecialization.pdf) 
  * Completed on Aug. 2024  
  * Course Contents:
    - FPGA computing systems: Background knowledge and introductory materials
    - FPGA computing systems: Partial Dynamic Reconfiguration
    - Developing FPGA-accelerated cloud applications with SDAccel: Theory
    - Developing FPGA-accelerated cloud applications with SDAccel: Practice

* <b>Hello FPGA</b> (Microchip University) [Certificate](https://verify.skilljar.com/c/866o372pn63s)  
  * Completed on Aug. 2024  
  * Course Contents:
    - Introduction to Microchip’s FPGA portfolio, including PolarFire FPGA and PolarFire SoC families
    - Architectural details of FPGA families, target applications, and available IP blocks
    - FPGA design flow using the Microchip Libero SoC toolset targeting the Hello FPGA platform

* <b>Computer and Peripheral Hardware</b> (Coursera) [Certificate](https://www.coursera.org/account/accomplishments/verify/OTSI90KYPL2G)  
  * Completed on Aug. 2024  
  * Course Contents:
    - Identify basic cable types and their connectors, features, and purposes.
    - Explain and configure motherboards, central processing units (CPUs), and add-on cards.
    - Demonstrate knowledge of several types of memory and their installation.

* <b>Google IT Automation with Python</b> (Coursera) [Certificate](https://www.coursera.org/account/accomplishments/specialization/529BUML5FSHT)  
  * Completed on Jul. 2024  
  * Course Contents:
    - Introduction to Git and GitHub
    - Using Python to Interact with the Operating System
    - Troubleshooting and Debugging Techniques
    - Automating Real-World Tasks with Python
    - Crash Course on Python
    - Configuration Management and the Cloud
    
English Proficiency
======
* TOEIC: <b>870</b> in Apr. 2024
* TOEFL: <b>98</b> in Sep. 2020

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Skills
======
* <b>Programming Languages</b>: C/C++, Python, C#
* <b>Software Tools</b>: Matlab (including Simulink), HTML/CSS, PyMesh, Blender, AutoCAD, FreeCAD, Inventor, PTC Creo
* <b>Hardware Platforms</b>: Arduino, STM32 (including FreeRTOS)

Activities
======
* Member of NTU Cycling Club (2021 – present)
* Private of The Republic of China Army (2020 – 2021)
* Chief Director of Executing at NTU Sunnykite Club (2016-2018)
* Editor of ASME NTU Student Section (2017-2018)
* Member of NTNU Bridge Club (2018)
* Honor of Summer Universiade Volunteer (2017)
