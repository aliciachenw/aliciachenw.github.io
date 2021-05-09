---
layout: single
title: "Academic Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

**Selected Academic Projects**

======
* SLAM for a ship welding robot
    * 16-833 Robot Localization and Mapping, Fall 2020, Carnegie Mellon University
    * Other members: Qindong Zhang, Ishraq Bhuiyan
    [Github](https://github.com/IshraqBhuiyan/slam_project)
    In this project we uses ICP-based SLAM and HDL and Kalman filter to localize a ship welding robot in a GPS-denied environment.

* Transfer learning for human detection in thermal images
    * 11-685 Introduction to Deep Learning, Fall 2020, Carnegie Mellon University
    * Other members: Ashley Kim, Ran Zhang, Jianchang Huang
    [Github](https://github.com/aliciachenw/11785-project-transfer-learning)
    This project we uses semi-supervised transfer learning method to use pre-trained faster R-CNN and YOLO to detect the pedestrian in the thermal images.


* Ultrasound speckle noise denoising with edge preservation
    * 16-725 Medical Image Analysis, Spring 2020, Carnegie Mellon University
    I implemented a classical [speckle reduction anisotropic diffusion (SRAD) filter](https://ieeexplore.ieee.org/abstract/document/1097762?casa_token=jbr0XBjReUoAAAAA:5VSU6ZPp58SCIlTv2tpWco_Ndtaow_l0-FWyvjgZ7Lzfip2TYSmHQ6EPOTHoSGJbWGYg7MxO)  in python, and improved the filter performance by adding histogram matching and edge preservation. I added histogram matching after several iterations to keep the contrast, and modified the original diffusion coefficient based on the result of Canny edge detector. I found that the new SRAD filter performs better in noise reduction and edge preservation, and have higher SSIM and Figure of Merit (FOM).
    ![SRAD](https://aliciachenw.github.io/images/project-SRAD.png)

* Optimization-based planning method for robot lifting
    * 16-741 Mechanics of Manipulation, Fall 2019, Carnegie Mellon University
    In this project, I implemented an optimization-based planning method, trying to minimize a goal function dened by the torque and the length of the trajectory. The project explores how different optimization goals influence the optimal trajectory, and finds that diffrent optimization goals sometimes can lead to similar results.
    ![Robot Arm Lifting Optimization](https://aliciachenw.github.io/images/project-lifting-optimization.png) -->

<!-- * Quadrilateral area coordinate method in finite element analysis
    * Finite Element Analysis, Spring 2018, Peking University
    In this project, I implemented a finite element analysis program using quadrilateral area coordinate (AQ4) in Fortran. I compared the performance of AQ4 with classical Q4, and found that AQ4 is more sensitive to the shape of elements, and has smaller stiffness than Q4.
    
* Country Fragility and Climate Change: Model and Case Studies
    * 2018 Interdisciplinary Contest in Modeling Competition, COMAP
    * Member: Wanwen Chen, Xiaoquan Gao, Xingsi Ren
    In this project, we constructed a mathematical model to measure country fragility, and also its correlation with climate changes. We designed new index named Country Fragility Index (CFI) to evaluate country fragility, considering economics, politics and security of countries. We then designed two regression models to explain CFI with climate changes, and our quadratic model (NLCI) with three variables had adjusted R-Square larger than 0.80 in most test cases. We then applied NLCI on Sudan and found the decline of arable land is the main reason of fragility in Sudan. The results are accord with former analytic researches. We then applied NLCI on China, and predicted CFI of China from now to 2100. We predict that CFI of China will continue to grow, and after 2042, the growth will be accompanied by severe fluctuation. 
    ![ICM](https://aliciachenw.github.io/images/project-ICM-2018.png)