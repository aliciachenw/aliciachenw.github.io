---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

Research Projects
======
* [Trauma Care In a Rusksack (TRACIR)](https://www.cmu.edu/news/stories/archives/2019/may/trauma-care-system.html)
    * Oct 2019 - present, Robotics Institute, Carnegie Mellon University

    I am currently involved in TRACIR project aiming at developing an autonomous catheter insertion. My responsibility is developing insertion detection and needle tracking algorithms that could work under different visibility.

* Sensor fusion algorithms for attitude measurement based on quaternions and kalman filter
    * Dec 2018 - Jul 2019, The Robotics Research Group, College of Engineering, Peking University

    This project is an undergraduate thesis project at Peking University. It aims at using Kalman Filter algorithm to fuse data from a nine-axis IMU (a three-axis acclerometer, a three-axis gyrometer and a three-axis magnetometer) to calculate its current attitude. We first analyzed the performance of three sensors using Allan Variance Analysis. We then compared the performance of Extended Kalman Filter and Unscented Kalman Filter, and implemented a simple but effective Adaptive Kalman Filter in simulation. We conducted experiments in three locomotion modes and found that our Adaptive Kalman Filter performs better than Extended Kalman Filter, that it has lower RMSE and also the ability to adapt poor initial estimation.
    ![Adaptive Kalman Filter](https://aliciachenw.github.io/images/project-akf.png)

* Analysis of Human Swimming Locomotion
    * Sep 2017 - May 2019, The Robotics Research Group, College of Engineering, Peking University
    [Publication](https://aliciachenw.github.io/publication/2020-05-08)

    This project is to use IMU to study human movement of swimming, and the characteristics and laws of muscle activity. In this project, I assisted in investigating previous swimming locomotion kinematics and energetic analysis methods. I implemented a joint angle measurement system based on IMU in both Matlab and C, and also compared the results from the system with those from optical motion capture system. The calculated angles are in accord with the ones measured by the optical motion capture system. I analyzed the angle of knees for four swimming strokes in one cycle and extracted both time domain and frequent domain features. The measured angles and features are in accord with the characters of each swimming stroke, and the accuracy of a simple linear SVM based on four simple time domain features is about 99%. 
    ![Swimming Locomotion Analysis](https://aliciachenw.github.io/images/project-imu-swimming.png)

* Human hand motion primitives during haptic search and retrieval of buried objects in sandbox
    * Jul 2018 - Sep 2018, Biomechatronics Lab, UCLA

    The motivation of this project is to understand hand movements during the task of searching and retrieving buried objects in a sandbox. The main study method is inspired by the methods in NLP because of the similarity between human movements and language. Motion primitives are often defined as the small units of human movements, and motion primitives are sequential data composed of static postures at certain time. It’s similar with our language, because sentences can be divided into words, and words can be divided into letters.

	We first used IMU sensors to capture human motion data. Then we calibrated the data from the sensors, because the data from each sensor was not generated from the same global coordinate system. We calculated anatomical angles as the features of postures, and used BIRCH algorithm to cluster the data. After we clustered the postures, we in fact transformed the continuous time-series data into a sequences of discrete postures. We then segmented the sequences into motion primitives through a 1s fixed window, and used the n-gram model, a widely used model in NLP, as the features of motion primitives. The motion primitives were clustered again in the same way of clustering postures. The center of a cluster is a typical motion primitive, and we used the closest posture sequence to animate it. We used SVM to classify motion intent. The n-gram model was used again as features of movements.
	
	I was responsible for the sensor calibration and movement animation in python, and the implementation of clustering and classification algorithms. This project was supported by CSST-UCLA program.
	![Motion Primitive](https://aliciachenw.github.io/images/project-motion-primitive.png)

* Environment-aware Locomotion Mode Recognition of Lower Limb Prostheses
	* Dec 2017 - Jul 2018, The Robotics Research Group, College of Engineering, Peking University
	[Publication 1](https://aliciachenw.github.io/publication/2019-01-24) [Publication 2](https://aliciachenw.github.io/publication/2018-10-25)

	Locomotion mode recognition can contribute to precise control of active lower-limb prostheses in different environments. In this paper, we propose a novel locomotion mode recognition method based on convolutional neural network and strain gauge signals. The strain gauge only provides one-dimensional signals and the convolutional neural network takes the raw noisy signals as inputs. The results show that the strain gauge contains information of locomotion modes, and the convolutional neural network has the capacity of extracting features from raw signals.
	
    My responsibilities include collaborating with lab partner to collect data, developing neural network models in Tensorflow and analyzing the algorithm performance.


Selected Academic Projects
======
* Ultrasound speckle noise denoising with edge preservation
    * 16-725 Medical Image Analysis, Spring 2020, Carnegie Mellon University

    I implemented a classical [speckle reduction anisotropic diffusion (SRAD) filter](https://ieeexplore.ieee.org/abstract/document/1097762?casa_token=jbr0XBjReUoAAAAA:5VSU6ZPp58SCIlTv2tpWco_Ndtaow_l0-FWyvjgZ7Lzfip2TYSmHQ6EPOTHoSGJbWGYg7MxO)  in python, and improved the filter performance by adding histogram matching and edge preservation. I added histogram matching after several iterations to keep the contrast, and modifyed the original diffusion coefficient based on the result of Canny edge detector. I found that the new SRAD filter performs better in noise reduction and edge preservation, and have higher SSIM and Figure of Merit (FOM).
    ![SRAD](https://aliciachenw.github.io/images/project-SRAD.png)


* Optimization-based planning method for robot lifting
    * 16-741 Mechanics of Manipulation Course Project, Fall 2019, Carnegie Mellon University

    This project is aiming at using the optimization-based planning method to let a 7-DOF robot arm lift an object from one pre-dened location to another location. In this project, I used Matlab to implement an optimization-based planning method, trying to minimize a goal function dened by the torque and the length of the trajectory. The project explores how different optimization goals influence the optimal trajectory, and finds that diffrent optimization goals sometimes can lead to similar results.
    ![Robot Arm Lifting Optimization](https://aliciachenw.github.io/images/project-lifting-optimization.png)

* Quadrilateral area coordinate method in finite element analysis
    * Finite Element Analysis, Spring 2018, Peking University

    In this project, I implemented a finite element analysis program using quadrilateral area coordinate (AQ4) in Fortran. I compared the performance of AQ4 with classical Q4, and found that AQ4 is more sensitive to the shape of elements, and has smaller stiffness than Q4.
    

* Country Fragility and Climate Change: Model and Case Studies
    * 2018 Interdisciplinary Contest in Modeling Competition, COMAP
    * Member: Wanwen Chen, Xiaoquan Gao, Xingsi Ren

    In this project, we constructed a mathematical model to measure country fragility, and also its correlation with climate changes. We designed new index named Country Fragility Index (CFI) to evaluate country fragility, considering economics, politics and security of countries. We then designed two regression models to explain CFI with climate changes, and our quadratic model (NLCI) with three variables had adjusted R-Square larger than 0.80 in most test cases. We then applied NLCI on Sudan and found the decline of arable land is the main reason of fragility in Sudan. The results are accord with former analytic researches. We then applied NLCI on China, and predicted CFI of China from now to 2100. The figure shows that CFI of China will continue to grow, and after 2042, the growth will be accompanied by severe fluctuation. 
    ![ICM](https://aliciachenw.github.io/images/project-ICM-2018.png)