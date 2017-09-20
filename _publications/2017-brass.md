---
title: 'A Cloud Robot System using the Dexterity Network and Berkeley Robotics and Automation as a Service (BRASS)'
authors: 'Nan Tian*, Matthew Matl*, Jeffrey Mahler, Yu Xiang Zhou, Samantha Staszak, Christopher Correa, Steven Zheng, Qiang Li, Robert Zhang, Ken Goldberg'
venue: 'IEEE International Conference on Robotics and Automation (ICRA)'
date: 2017-05-29
category: 'published'
pdf: '2017-brass.pdf'
bibtex: '2017-brass.bib'
teaser: '2017-brass.png'
permalink: /publication/2017-brass
collection: publications
---

Abstract
-------
Robotics and Automation as a Service (RAaaS), the robotics-equivalent of Software as a Service (SaaS), can serve as an important component in a cloud robotics framework by avoiding complex software installation and maintenance, reducing application development time, and facilitating sharing of data. However, RAaaS may introduce network latency and security issues. This paper describes an implemented RAaaS system architecture and reports on physical grasping experiments. The system uses Berkeley RAaaS Software (Brass) to remotely host an instance of Dex-Net 1.0, a robust grasp-planning system that samples grasps on 3D object meshes and computes stochastic robustness metrics for each grasp. The system links a local ABB YuMi human-safe robot with Brass via a cross-border, secure, and low-latency network provided by Cloudminds, Inc. We study grasp performance under this architecture by programming the YuMi to grasp and lift a set of non-standard, asymmetric chess pieces. Results suggest that the RAaaS system can provide significant improvements in grasp robustness with reasonable mean network latency times of 30 ms and 200 ms for servers 500 and 6000 miles away from the robot, respectively.

