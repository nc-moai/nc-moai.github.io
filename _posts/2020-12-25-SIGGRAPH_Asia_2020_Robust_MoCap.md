---
title: "SIGGRAPH Asia 2020: A Robust Low-cost Mocap System with Sparse Sensors"
image: 
  path: /images/posts/null.png
  thumbnail: /images/posts/2020-12-25-Robust_MoCap.png
date: 2020-12-25 08:39:00
categories:
  - Conference
author: dtrca
---

컴퓨터 그래픽스 학회인 SIGGRAPH Asia 2020 Motion AI 팀의 A Robust Low-cost Mocap System with Sparse Sensors 연구가 소개되었습니다.

<figure class="align-center">
  <a href="#"><img src="{{ '/images/posts/2020-12-25-Robust_MoCap.png' | absolute_url }}" alt=""></a>
</figure>

### Abstract

In this paper, we propose a robust low-cost mocap system (mocap) with sparse sensors. Although the sensor with an accelerometer, magnetometer, and gyroscope is cost-effective and offers the measured positions and rotations from these devices, it potentially suffers from noise, drift, and lost issues over time. The resulting character obtained from a sensor-based low-cost mocap system is thus generally not satisfactory. We address these issues by using a novel deep learning framework that consists of two networks, a motion estimator and a sensor data generator. When the aforementioned issues occur, the motion estimator feeds the newly synthesized sensor data obtained with the measured and predicted data from the sensor data generator until the issues have been resolved. Otherwise, the motion estimator receives the measured sensor data to accurately and continuously reconstruct the new character poses. In our examples, we show that our system outperforms the previous approach without the sensor data generator and we believe that it can be considered a handy and robust mocap system.

### Authors

Seong Uk Kim(Kangwon National University), Hanyoung Jang(NCSOFT), Jongmin Kim(Kangwon National University)

[ A Robust Low-cost Mocap System with Sparse Sensors](https://nc-moai.github.io/papers/SIGGRAPH_AISA_ABSTRACT_2020.pdf)

### Proceeding

SIGGRAPH Asia '20 ACM SIGGRAPH 2020 Poster Article