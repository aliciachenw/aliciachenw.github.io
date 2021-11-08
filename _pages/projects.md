---
layout: single
title: "Selected Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

<!-- * Smart UI for AR display in Operation Room
    * MARSS
    * Other members:  -->

* Transformer for needle tracking
    * 16-824 Visual Learning and Recognition, Spring 2021, Carnegie Mellon University
    * Other members: Alex Hung, Muyu Ouyang

    [Page](https://sites.google.com/andrew.cmu.edu/16824-project/home) [Github](https://github.com/aL3x-O-o-Hung/TransformerForUltrasoundNeedleTracking)
    
    We explore using a U-transformer and multiple combinations of the model structures to track the inserted needle in ultrasoung images.

* SLAM for a ship welding robot
    * 16-833 Robot Localization and Mapping, Fall 2020, Carnegie Mellon University
    * Other members: Qindong Zhang, Ishraq Bhuiyan
    
    [Github](https://github.com/IshraqBhuiyan/slam_project)
    
    We use ICP-based SLAM, HDL and Kalman filter to localize a ship welding robot in a GPS-denied environment.

* Transfer learning for human detection in thermal images
    * 11-685 Introduction to Deep Learning, Fall 2020, Carnegie Mellon University
    * Other members: Ashley Kim, Ran Zhang, Jianchang Huang
    
    [Github](https://github.com/aliciachenw/11785-project-transfer-learning) [Presentation](https://www.youtube.com/watch?v=uHPqJcPMQDw) [Report](https://drive.google.com/file/d/1SSWwAOS04VDqUeSrs6hrdaNefBIYWp33/view)
    
    We explore transfer learning and active learning methods to detect the pedestrian in the thermal images using faster R-CNN and YOLO.

* Ultrasound speckle noise denoising with edge preservation
    * 16-725 Medical Image Analysis, Spring 2020, Carnegie Mellon University
    
    I implemented a classical [speckle reduction anisotropic diffusion (SRAD) filter](https://ieeexplore.ieee.org/abstract/document/1097762?casa_token=jbr0XBjReUoAAAAA:5VSU6ZPp58SCIlTv2tpWco_Ndtaow_l0-FWyvjgZ7Lzfip2TYSmHQ6EPOTHoSGJbWGYg7MxO) in python, and improved the filter performance by adding histogram matching and edge preservation. I added histogram matching after several iterations to keep the contrast, and modified the original diffusion coefficient based on the result of Canny edge detector. I found that the new SRAD filter performs better in noise reduction and edge preservation, and have higher SSIM and Figure of Merit (FOM).

* Optimization-based planning method for robot lifting
    * 16-741 Mechanics of Manipulation, Fall 2019, Carnegie Mellon University
    
    I implemented an optimization-based planning method trying to minimize a goal function defined by the torque and the length of the trajectory. The project explores how different optimization goals influence the optimal trajectory.
