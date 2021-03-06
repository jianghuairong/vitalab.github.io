---
layout: review
title: "Deep Level Sets for Salient Object Detection"
author: Zhiming Luo
tags: deep-learning CNN segmentation
pdf:   "http://openaccess.thecvf.com/content_cvpr_2017/papers/Hu_Deep_Level_Sets_CVPR_2017_paper.pdf"
cite:
    authors: "P. Hu, B. Shuai, J. Liu, and G. Wang"
    title:   "Deep Level Sets for Salient Object Detection"
    venue:   "CVPR 2017"
---


## Contributions

- Form the saliency detection as a deep level set optimization problem
- Guided Super-pixel Filtering to propagate saliency information

## Deep level sets for salient object detection


### 1. Formulation of Level Sets

![](/deep-learning/images/deeplevelset/fig2.jpg)
![](/deep-learning/images/deeplevelset/fig2_1.jpg)

### 2. Level sets for Deep saliency

#### The energy function

![](/deep-learning/images/deeplevelset/eqn1.jpg)

#### Average saliency values

![](/deep-learning/images/deeplevelset/eqn2.jpg)

#### Gradients

![](/deep-learning/images/deeplevelset/eqn3.jpg)

## Guided Super-pixel Filtering

1. Guided image [filter](http://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=6319316&tag=1) is an explicit image filtering algorithm,
edge-preserving and gradient-preserving

2. Over segment image into super-pixels and do a graph-based guided filtering

![](/deep-learning/images/deeplevelset/fig4.jpg)


![](/deep-learning/images/deeplevelset/eqn4.jpg)
![](/deep-learning/images/deeplevelset/eqn5.jpg)

## Experiments Results

![](/deep-learning/images/deeplevelset/tab1.jpg)

