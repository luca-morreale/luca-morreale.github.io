---
layout: post
title: "Predicting the Next Best View for 3D Mesh Refinement"
authors: [lmorreale, aromanoni, mmatteucci]
webpage: /photometric-next-best-view-for-drones/
pdf: https://arxiv.org/pdf/1805.06207
code: https://github.com/luca-morreale/stochastic-nbv-4-mesh-refinement
thumbnail: photometric_thumbnail.png 
summary: Next Best View prediction based on photogrammetry principles."

date: 2018-05-21 16:39:18
comments: false
description: "Next Best View for Drones"
keywords: "NBV"
categories:
- projects
img: photometric.png # Add image post (optional)
tags: [Robotics, Perception, 3D Reconstruction, Computer Vision] # add tag
---

**Abstract:** 3D reconstruction is a core task in many applications such as robot navigation or sites inspections. Finding the best poses to capture part of the scene is one of the most challenging topic that goes under the name of Next Best View. Recently many volumetric methods have been proposed; they choose the Next Best View by reasoning into a 3D voxelized space and by finding which pose minimizes the uncertainty decoded into the voxels. Such methods are effective but they do not scale well since the underlaying representation requires a huge amount of memory. In this paper we propose a novel mesh-based approach that focuses the next best view on the worst reconstructed region of the environment. We define a photo-consistent index to evaluate the model accuracy, and an energy function over the worst regions of the mesh that takes into account the mutual parallax with respect to the previous cameras, the angle of incidence of the viewing ray to the surface and the visibility of the region. We tested our approach over a well known dataset and achieve state-of-the-art results.

{% comment %}
Among the many task an autonomous robot can have mapping is one of the most important and targeted lately in robotics due to its complexity. Think of a robot exploring an old cave, in case the map in not reliable the robot may not make it back. Therefore, mapping is a key task.

As for this project we address the task of mapping from a 3D reconstruction perspective. Differently from state of the art approaches, which mostly rely on counting procedure over a volumetric representation, we use triangular mesh representation and use it to efficiently estimate the Next Best View, i.e., the next optimal pose from which observe the environment.
As further distinction, our approach evaluates the reconstruction accuracy to select areas which are not properly reconstructed. Then, the optimal pose is identified by optimizing an energy function, devised based on several known criteria used in photogrammetry and computer vision.
Based on the selected areas, our approach can jointly favor exploration and refinement.
{% endcomment %}


{% comment %}
I worked on this research project, as my master thesis, alongside professor Matteo Matteucci and PhD Andrea Romanoni. The goal was to estimate the accuracy of the reconstruction and use it to identify a pose for a new picture to be captured so to enhance it. Thanks to results we obtained we published an article at IAS-15 which has been accepted for oral presentation, and we are currently working on an extended version for a journal.
{% endcomment %}

#### Related Links

[[PDF]({{page.pdf}})][[CODE]({{page.code}})] L. Morreale, A. Romanoni, M. Matteucci. *Predicting the Next Best View for 3D Mesh Refinement* **@** IAS-15

#### Bibtex
```
@inproceedings{morreale2018predicting,
  title={Predicting the Next Best View for 3D Mesh Refinement},
  author={Morreale, Luca and Romanoni, Andrea and Matteucci, Matteo},
  booktitle={International Conference on Intelligent Autonomous Systems},
  pages={760--772},
  year={2018},
  organization={Springer}
}
```

