---
title: "Realtime Terrain Adaptive IK Motion Synthesis using Deep-learning"
image:
  path: /images/posts/null.png
  thumbnail: /images/research/2020-10-23-IK.png
date: 2019-04-12 15:51:00
categories:
  - Research
tags:
  - Inverse Kinematics
author: ncdrjang
---

게임 환경에서 실시간으로 동작하는 IK 모션 생성에 대한 연구를 진행 중 입니다.

<video width="560" height="315" controls>
  <source src="/images/posts/2019-04-12-IK_Video_Compare.mp4" type="video/mp4">
</video>

특히 임의의 굴곡 있는 벽면을 올라가는 캐릭터를 대상으로 자연스러운 동작으로 특정 지점을 정확히 잡는 것을 목표로 합니다.

기존 방법들의 부자연스러움과 실시간 동작에 대한 연산량의 한계를 극복하기 위해 neural-network 기반의 기계학습 방법을 도입하였습니다.

<video width="560" height="315" controls>
  <source src="/images/posts/2019-04-12-IK_Video_Demo.mp4" type="video/mp4">
</video>

실시간으로 벽면의 충돌 지점을 확인하고 다음 경로를 결정하고 포즈를 생성합니다.

<video width="560" height="315" controls>
  <source src="/images/posts/2019-04-12-IK_Video_Performance.mp4" type="video/mp4">
</video>

약 1ms의 연산 시간으로 수 십명의 캐릭터 애니메이션을 재생할 수 있습니다.