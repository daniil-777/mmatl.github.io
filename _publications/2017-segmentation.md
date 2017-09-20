---
title: 'An Algorithm for Transferring Parallel-Jaw Grasps Between 3D Mesh Subsegments'
authors: 'Matthew Matl, Jeffrey Mahler, Ken Goldberg'
venue: 'IEEE International Conference on Automation Science and Engineering (CASE)'
date: 2017-08-21
category: 'published'
pdf: '2017-segmentation.pdf'
bibtex: '2017-segmentation.bib'
teaser: '2017-segmentation.png'
permalink: /publication/2017-segmentation
collection: publications
---

Abstract
-------
In this paper, we present an algorithm that improves the rate of successful grasp transfer between 3D mesh models by breaking each mesh into functional subsegments and transferring grasps between similar subsegments rather than between full models. This algorithm combines prior research on grasp transfer with mesh segmentation techniques from computer graphics to successfully transfer contact points more often while potentially preserving task-specific knowledge across transfers. The algorithm extracts subsegments from each mesh model with a customized segmentation algorithm designed for speed and then groups similar subsegments with D2 shape descriptors and Gaussian mixture models (GMMs). Grasps are then transferred by aligning similar subsegments with Super4PCS, a global point cloud registration algorithm. We experimentally evaluated this algorithm against a nonsegmenting baseline on over 20,000 grasp transfers across a set of 80 objects and found that the segmentation-based algorithm improved the success rate for finding a transferred grasp from 82% to 98%. Additionally, grasps transferred with our algorithm were only 8.7% less robust on average than the original grasps without any local re-planning.


