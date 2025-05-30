---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

**Current**

* **Tissue Tracking and Landmark Retrieval in Ultrasound**, *Jan 2023 - present*
    *  Robotics and Control Laboratory, The University of British Columbia

    I am broadly interested in representation learning and/or self-supervising learning for ultrasound image analysis. Recently, I am exploring this question: how can the models learn pixel or frame-wise representations for ultrasound that can be applied in down-stream tasks, such as tracking and information intrieval?

    *  I developed a new tracking-any-point model for US that outperforms state-of-the-art optical flow in [*ASMUS 2024*](https://link.springer.com/chapter/10.1007/978-3-031-73647-6_5), [*arXiv*](https://arxiv.org/abs/2403.04969).

    * I also developed a self-supervised representation learning approach for US view retrieval and proposed a novel method to leverage intra-sweep temporal information to improve classical contrastive learning:  [*arXiv*](https://arxiv.org/abs/2412.07741), [IJCARS](https://link.springer.com/article/10.1007/s11548-025-03394-1).

* **Ultrasound Guidance for Transoral Robotic Surgery**, *Sep 2021 - present*
    *  Robotics and Control Laboratory, The University of British Columbia

    Head and neck-related cancers account for a large percentage of all cancers globally, and transoral robotic surgery (TORS) shows the potential to help preserve the function of the patients after the treatment. However, TORS is challenging because it requires surgeons to have profound knowledge of anatomy. We hypothesize that ultrasound guidance can improve treatment outcomes in head and neck cancers, and we aim at developing novel ultrasound technologies for robotic-assisted surgery. 

    My research built an augmented reality system for TORS. I conducted system design and prototyped  the first ultrasound (US)-guided augmented reality systems for TORS. The work is published in [*IJCARS 2023*](https://link.springer.com/article/10.1007/s11548-023-02898-y), and a free preprint version can be found on [*arXiv*](https://arxiv.org/abs/2211.16544).

    To make the system more intelligent, I am developing methods for head-and-neck MRI, CT, and US segmentation and registration to automate the system registration and calibration process.
    * MRI-US registration feasibility study: [*SPIE: Medical Imaging 2023*](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/12466/1246625/Feasibility-of-MRI-US-registration-in-oropharynx-for-transoral-robotic/10.1117/12.2655032.short)
    * Point cloud registration using semantic informaiton and biomechanical energy regularization: [*arXiv*](https://arxiv.org/abs/2503.00972)

    We also explore using robot to perform US scan during TORS in [*IJCARS 2024*](https://link.springer.com/article/10.1007/s11548-024-03160-9).
    


**Past Projects**

* **AI in Lung Ultrasound COVID-19 Diagnosis and Segmentation**, *Nov 2020 - Aug 2021*
    *  Biomedical Image Guidance Lab, Carnegie Mellon University
    *  [*MICCAI LL-COVID19 Workshop 2021*](https://link.springer.com/chapter/10.1007/978-3-030-90874-4_14)
    
    This project is aiming at developing AI tools for ultrasound image analysis. I worked on developing lung region segmentation algorithms, and it was further used to evaluate how different regions in lung ultrasound images affect AI accuracy in COVID-19 severity classification. I also worked on using optical flow to improve the semantic segmentation accuracy of lung ultrasound.

* **Modeling and Motion Planning for Lateral Manipulation of Needle Steering**, *Sep 2020 - Aug 2021*
    *  Biomedical Image Guidance Lab, Carnegie Mellon University
    *  [*Thesis*](https://www.ri.cmu.edu/publications/ultrasound-based-needle-tracking-and-lateral-manipulation-planning-for-common-needle-steering/)

    This project is a part of my master thesis at Carnegie Mellon Univeristy. The project is targeting at using lateral manipulation at the needle base to control the needle steering. I improved a previous mechanical model to model the needle-tissue interaction and bending and also developed two different replanning algorithms without the need for humans to select the first insertion point.

* **Needle Tracking in Ultrasound Images**, *Oct 2019 - Aug 2021*
    * Biomedical Image Guidance Lab, Carnegie Mellon University
    * Dual-path bending needle tracking: [*ISBI 2021*](https://ieeexplore.ieee.org/abstract/document/9433804) 
    * [*Thesis*](https://www.ri.cmu.edu/publications/ultrasound-based-needle-tracking-and-lateral-manipulation-planning-for-common-needle-steering/)

    My research focused on ultrasound-based needle tracking.  I introduced new algorithms to track a needle robustly under challenging situations such as that the needle is bending or it is partially visible. I first developed a novel bending needle tracking algorithm that utilizes the kinematic consistency in the segmentation to improve the tracking accuracy. I also designed a new information fusion-based tracking algorithm, which can utilize both robot forward kinematics and ultrasound-based segmentation to track a needle robustly. The algorithm can recalibrate the transformation parameters between the robot forward kinematics and the ultrasound image coordinates to improve the insertion accuracy. I also developed a new needle detection algorithm which utilizes the micro-motion in the tissue to estimate the location of the needle.

* **Sensor Fusion for Attitude Measurement Based on Quaternions and Kalman Filter**, *Dec 2018 - Jul 2019*
    * The Robotics Research Group, Peking University

    This project is for my undergraduate thesis at Peking University. It aims at using Kalman Filter algorithm to fuse data from a nine-axis IMU (a three-axis acclerometer, a three-axis gyrometer and a three-axis magnetometer) to calculate its current attitude. 

* **Analysis of Human Swimming Locomotion**, *Sep 2017 - May 2019*
    * The Robotics Research Group, Peking University
    * Applied system: [*IEEE TMRB*](https://ieeexplore.ieee.org/abstract/document/9090211/)

    This project is to use IMU to study human movement of swimming, and the characteristics and laws of muscle activity. 
    I investigated previous swimming locomotion kinematics and energetic analysis methods, implemented a joint angle measurement system based on IMU in both Matlab and C and compared the results from the system with those from optical motion capture system. 

* **Human Hand Motion Primitives During Haptic Search and Retrieval of Buried Objects in Sandbox**, *Jul 2018 - Sep 2018*
    * Biomechatronics Lab, UCLA

    The motivation of this project is to understand hand movements during the task of searching and retrieving buried objects in a sandbox. The main study method is inspired by the methods in NLP because of the similarity between human movements and language. Motion primitives are often defined as the small units of human movements, and motion primitives are sequential data composed of static postures at certain time. It’s similar with our language, because sentences can be divided into words, and words can be divided into letters. So we use models in NLP to model motion primitives.

* **Environment-aware Locomotion Mode Recognition of Lower Limb Prostheses**, *Dec 2017 - Jul 2018*
	* The Robotics Research Group, Peking University
    * [*Advanced Robotics*](https://www.tandfonline.com/doi/abs/10.1080/01691864.2018.1563500)

	Locomotion mode recognition can contribute to precise control of active lower-limb prostheses in different environments. We propose a novel locomotion mode recognition method based on convolutional neural network and strain gauge signals. The strain gauge only provides one-dimensional signals and the convolutional neural network takes the raw noisy signals as inputs.
