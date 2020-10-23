---
title: "CASA 2020: A Variational U-Net for Motion Retargeting"
image: 
  path: /images/posts/null.png
  thumbnail: /images/posts/2020-10-09-U-Net.png
date: 2020-10-08 16:43:30
categories:
  - Conference
author: dtrca
---

컴퓨터 그래픽스 학회인 CASA 2020에 Motion AI 팀의 A Variational U-Net for Motion Retargeting 연구가 소개되었습니다.

해당 논문은 우수논문상 후보에 올랐습니다.

<figure class="align-center">
  <a href="#"><img src="{{ '/images/posts/2020-10-23-CASA_Nominee.png' | absolute_url }}" alt=""></a>
</figure>

### Abstract

Motion retargeting is the process of copying motion from one character(source) to another(target) when the source and target body sizes and proportions(of arms, legs, torso, and so on) are different. The problem of automatic motion retargeting has been studied for several decades; however, the motion quality obtained with the application of current approaches is on occasion unrealistic. To address these issues, we present a novel human motion retargeting system using a deep learning framework with large-scale motion data to produce high-quality retargeted human motion. We establish a deep-learning-based motion retargeting system using a variational deep autoencoder combining the deep convolutional inverse graphics network(DC-IGN) and the U-Net. The DC-IGN is utilized for disentangling the motion of each body part, while the U-Net is employed to preserve details of the original motion.

<figure class="align-center">
  <a href="#"><img src="{{ '/images/posts/2020-10-09-U-Net.png' | absolute_url }}" alt=""></a>
</figure>

### Authors

Seong Uk Kim(Kangwon National University), Hanyoung Jang(NCSOFT), Jongmin Kim(Kangwon National University)

[A variational U-Net for motion retargeting](https://onlinelibrary.wiley.com/doi/abs/10.1002/cav.1947)

### Related Posts

[SIGGRAPH Asia 2018: A Variational U-Net for Motion Retargeting](/conference/Variational_U-Net/)