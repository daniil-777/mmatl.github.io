---
title: 'Dex-Net 3.0: Computing Robust Robot Suction Grasp Targets using a New Analytic Model and Deep Learning'
authors: 'Jeffrey Mahler, Matthew Matl, Xinyu Liu, Albert Li, David Gealy, Ken Goldberg'
venue: 'IEEE International Conference on Robotics and Automation (IRCA)'
date: 2018-05-28
category: 'submitted'
pdf: '2018-suction.pdf'
teaser: '2018-suction.png'
supplement: '2018-suction-supplement.pdf'
extended: '2018-suction-extended.pdf'
permalink: /publication/2018-suction
collection: publications
---

Abstract
-------
Suction-based end effectors are widely used in industry and are often preferred over parallel-jaw and multifinger grippers due to their ability to lift objects with a single point of contact. This ability simplifies planning, and hand- coded heuristics such as targeting planar surfaces are often used to select suction grasps based on point cloud data. In this paper, we propose a compliant suction contact model that computes the quality of the seal between the suction cup and target object and determines whether or not the suction grasp can resist an external wrench (e.g. gravity) on the object. To evaluate a grasp, we measure robustness to perturbations in end-effector and object pose, material properties, and external wrenches. We use this model to generate Dex-Net 3.0, a dataset of 2.8 million point clouds, suction grasps, and grasp robustness labels computed with 1,500 3D object models and we train a Grasp Quality Convolutional Neural Network (GQ-CNN) on this dataset to classify suction grasp robustness from point clouds. We evaluate the resulting system in 375 physical trials on an ABB YuMi fitted with a pneumatic suction gripper. When the object shape, pose, and mass properties are known, the model achieves 99% precision on a dataset of objects with Adversarial geometry such as sharply curved surfaces. Furthermore, a GQ-CNN-based policy trained on Dex-Net 3.0 achieves 99% and 97% precision respectively on a dataset of Basic and Typical objects.
