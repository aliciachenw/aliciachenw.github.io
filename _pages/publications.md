---
layout: single
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

<!-- {% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->

You can also find my articles on [Google Scholar](https://scholar.google.com/citations?user=jS9csA4AAAAJ&hl=en).

**Conferences**

3. **W. Chen**, K. Mehta, B. D. Bhanushali, J. Galeotti, "Ultrasound-based Tracking of Partially In-plane, Curved Needles". (Accepted by *2021 International Symposium on Biomedical Imaging (ISBI)*).

    We propose a novel curve needle tracking method which utilizes a novel weighted RANSAC and probabilistic Hough transform with kinematics reference to track a curved and partially visible needle in ultrasound images. 
    The method works robustly and outperforms RANSAC, probabilistic Hough transform, and deep-learning based model in tracking a pre-bent needle in ultrasound phantom, and in tracking a naturally bent needle in actual tissue.

2. A. L. Y. Hung, **W. Chen**, J. Galeotti, "Ultrasound Confidence Maps of Intensity and Structure Based on Directed Acyclic Graphs and Artifact Models," arXiv preprint arXiv:2011.11956 (Accepted by *2021 International Symposium on Biomedical Imaging (ISBI)*). [link](https://arxiv.org/pdf/2011.11956.pdf) 

    We use a direct acyclic graph-based method to analyize the pixel confidence in ultrasound images. We demonstrate unique capabilities of our approach and compare it against previous confidence-measurement algorithms for shadow-detection and image-compounding tasks.

1. J. Mai, **W. Chen**, S. Zhang, D. Xu and Q. Wang, "Performance analysis of hardware acceleration for locomotion mode recognition in robotic prosthetic control," *2018 IEEE International Conference on Cyborg and Bionic Systems (CBS)*, Shenzhen, 2018, pp. 607-611. [link](https://ieeexplore.ieee.org/abstract/document/8612257?casa_token=4oRbYfiN1HQAAAAA:EWHcB37LQNATyO7mY_GeaKUKzDWqhqBITOBm7TEar1kNbSKVDzcb_vSNTLvw3U2PL6u_rU4)

    We analyze the computing performance of an on-board locomotion mode recognition system which was designed for robotic transtibial prosthesis. We implemented FPGA on-board support vector machine, back-propagation neural network, quadratic discriminant analysis and linear discriminant analysis, and the experiments demonstrated that the proposed system can provide satisfactory acceleration effects on the four applied algorithms.

**Journals**

2. Q. Wang et al., "An Underwater Lower-Extremity Soft Exoskeleton for Breaststroke Assistance," *IEEE Transactions on Medical Robotics and Bionics*, vol. 2, no. 3, pp. 447-462, Aug. 2020. [link](https://ieeexplore.ieee.org/document/9090211)

    We designed an underwater lower-extremity soft exoskeleton called Powered Swimsuit to assist the wearer in breaststroke with fins. The assistive force was applied to the bottom of the fins via soft cables. During the propelling period of the stroke cycle, the cables pulled the ankle joints to provide assistance to plantar flexion. 
    <!-- Compared with breaststroke without assistance, the decrease in the peak of surface electromyography in the sweep phase with the exoskeleton assistance showed the feasibility of the proposed Powered Swimsuit in underwater motion assistance. -->

1. Y. Feng\*, **W. Chen\***, and Q. Wang, "A strain gauge based locomotion mode recognition method using convolutional neural network," *Advanced Robotics*, vol. 33, no. 5, pp. 254-263, Jan. 2019. [link](https://www.tandfonline.com/doi/abs/10.1080/01691864.2018.1563500)
(\* means equal contribution)

    We propose a novel locomotion mode recognition method based on convolutional neural network and strain gauge signals. The overall three-class locomotion mode recognition accuracy shows that the strain gauge contains information of locomotion modes, and the convolutional neural network has the capacity of extracting features from raw signals.