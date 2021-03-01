---
layout: post
title: "Dense 3D Visual Mapping via Semantic Simplification"
authors: [lmorreale, aromanoni, mmatteucci]
webpage: /mesh-semantic-simplification/
pdf: https://arxiv.org/pdf/1902.07511.pdf
thumbnail: probabilistic_view07.png 
summary: "Fast scene point cloud simplification leveraging semantic information."

date: 2018-07-15 15:09:48
comments: false
description: "Dense 3D Visual Mapping via Semantic Simplification"
keywords: ""
categories:
- projects
img: probabilistic_view07.png # Add image post (optional)
tags: [3D Reconstruction, Computer Vision, Machine Learning, Semantic Segmentation, SVM] # add tag
---

**Abstract:** Dense 3D visual mapping estimates as many as possible pixel depths, for each image. This results in very dense point clouds that often contain redundant and noisy information, especially for surfaces that are roughly planar, for instance, the ground or the walls in the scene. In this paper we leverage on semantic image segmentation to discriminate which regions of the scene require simplification and which should be kept at high level of details. We propose four different point cloud simplification methods which decimate the perceived point cloud by relying on class-specific local and global statistics still maintaining more points in the proximity of class boundaries to preserve the infra-class edges and discontinuities. 3D dense model is obtained by fusing the point clouds in a 3D Delaunay Triangulation to deal with variable point cloud density. In the experimental evaluation we have shown that, by leveraging on semantics, it is possible to simplify the model and diminish the noise affecting the point clouds.


#### Related Links

[[PDF]({{page.pdf}})] L. Morreale, A. Romanoni, M. Matteucci. *Dense 3D Visual Mapping via Semantic Simplification* **@** ICRA 2019

#### Bibtex
```
@inproceedings{morreale2019dense,
  title={Dense 3D visual mapping via semantic simplification},
  author={Morreale, Luca and Romanoni, Andrea and Matteucci, Matteo and di Milano, Politecnico},
  booktitle={2019 International Conference on Robotics and Automation (ICRA)},
  pages={6891--6897},
  year={2019},
  organization={IEEE}
}
```
