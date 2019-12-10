---
title: "SIGGRAPH 2019 Asia: Fast Terrain-Adaptive Motion Generation using Deep Neural Networks"
date: 2019-09-26 17:18:00
categories:
  - News
author: requiem4546
---

We propose a fast motion adaptation framework using deep neural networks. Traditionally, motion adaptation is performed via iterative numerical optimization.We adopted deep neural networks and replaced the iterative process to the feed-forward inference which consists of simple matrix multiplications. For efficient mapping from contact constraints to character motion, the proposed system is composed of two types of networks: trajectory and pose generators. The networks are trained using augmented motion capture data and are fine-tuned using the inverse kinematics loss. In experiments, our system successfully generates multi-contact motions of a hundred of characters in real-time, and the result motions contain the naturalness existing in the motion capture data.

<iframe width="560" height="315" src="https://www.youtube.com/embed/4DpwvWe9hOM" frameborder="0" allow="accelerometer; autoplay;encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>

### Authors

Moonwon Yu, Byungjun Kwon, Hanyoung Jang(NCSOFT), Jongmin Kim, Shinjin Kang

### Proceeding

SIGGRAPH Asia '19 ACM SIGGRAPH 2019 Technical Brief 