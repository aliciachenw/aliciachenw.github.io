---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

**Current**

* **Modeling and Motion Planning for Lateral Manipulation of Needle Steering**, *Sep 2020 - present*
    *  Robotics Institute, Carnegie Mellon University

    This project is for my master thesis at Carnegie Mellon Univeristy. The project is targeting at using lateral manipulation at the needle base to control the needle steering. 

* **[Trauma Care In a Rusksack (TRACIR)](https://www.cmu.edu/news/stories/archives/2019/may/trauma-care-system.html)**, *Oct 2019 - present*
    * Robotics Institute, Carnegie Mellon University
    <!-- * Publication: coming soon -->

    TRACIR is aiming at developing autonomous catheter insertion. My responsibility is developing insertion detection and needle tracking algorithms that could work under different visibility. I develop a tracking fusion algorithm that combine the estimation from robotic kinematics and ultrasound-based tracking, and also introduce a new needle detection algorithm which utilizes the micro-motion in the tissue to estimate the location of the needle.



**Past Projects**

* **Sensor Fusion for Attitude Measurement Based on Quaternions and Kalman Filter**, *Dec 2018 - Jul 2019*
    * The Robotics Research Group, Peking University

    This project is for my undergraduate thesis at Peking University. It aims at using Kalman Filter algorithm to fuse data from a nine-axis IMU (a three-axis acclerometer, a three-axis gyrometer and a three-axis magnetometer) to calculate its current attitude. 
    <!-- I analyzed the performance of three sensors using Allan Variance Analysis, implemented the performance of Extended Kalman Filter and Unscented Kalman Filter, and a simple but effective Adaptive Kalman Filter. After testing three algorithms in simulation and experiments in three locomotion modes, I found that our Adaptive Kalman Filter performs better than Extended Kalman Filter, with lower RMSE and also the ability to adapt poor initial estimation.
     -->
    <!-- ![Adaptive Kalman Filter](https://aliciachenw.github.io/images/project-akf.png) -->

* **Analysis of Human Swimming Locomotion**, *Sep 2017 - May 2019*
    * The Robotics Research Group, Peking University
    * [Publication](https://ieeexplore.ieee.org/abstract/document/9090211/)

    This project is to use IMU to study human movement of swimming, and the characteristics and laws of muscle activity. 
    I investigated previous swimming locomotion kinematics and energetic analysis methods, implemented a joint angle measurement system based on IMU in both Matlab and C and compared the results from the system with those from optical motion capture system. 
    <!-- The calculated angles are in accord with the ones measured by the optical motion capture system. I analyzed the angle of knees for four swimming strokes in one cycle and extracted both time domain and frequent domain features, and the measured angles and features are in accord with the characters of each swimming stroke, and the accuracy of a simple linear SVM based on four simple time domain features achieve high accuracy in stroke recognition.  -->
    <!-- ![Swimming Locomotion Analysis](https://aliciachenw.github.io/images/project-imu-swimming.png) -->

* **Human Hand Motion Primitives During Haptic Search and Retrieval of Buried Objects in Sandbox**, *Jul 2018 - Sep 2018*
    * Biomechatronics Lab, UCLA

    The motivation of this project is to understand hand movements during the task of searching and retrieving buried objects in a sandbox. The main study method is inspired by the methods in NLP because of the similarity between human movements and language. Motion primitives are often defined as the small units of human movements, and motion primitives are sequential data composed of static postures at certain time. It’s similar with our language, because sentences can be divided into words, and words can be divided into letters. So we use models in NLP to model motion primitives.
    
    <!-- My work includes calibrating IMU sensors, programming for the movement animation in python and implementing the motion primitive clustering and classification algorithms -->
	<!-- ![Motion Primitive](https://aliciachenw.github.io/images/project-motion-primitive.png) -->

* **Environment-aware Locomotion Mode Recognition of Lower Limb Prostheses**, *Dec 2017 - Jul 2018*
	* The Robotics Research Group, Peking University
	<!-- * [Publication 1](https://aliciachenw.github.io/publication/2019-01-24) [Publication 2](https://aliciachenw.github.io/publication/2018-10-25) -->
    * [Publication](https://www.tandfonline.com/doi/abs/10.1080/01691864.2018.1563500)

	Locomotion mode recognition can contribute to precise control of active lower-limb prostheses in different environments. We propose a novel locomotion mode recognition method based on convolutional neural network and strain gauge signals. The strain gauge only provides one-dimensional signals and the convolutional neural network takes the raw noisy signals as inputs.
    <!-- 	
    I collaborated with lab partner to collect data and developed the neural network models in Tensorflow and analyze the algorithm performance. The results show that the strain gauge contains information of locomotion modes, and the convolutional neural network has the capacity of extracting features from raw signals. -->
    <!-- ![Locomotion Mode Recognition](https://aliciachenw.github.io/images/project-cnn-prothesis.png) -->


