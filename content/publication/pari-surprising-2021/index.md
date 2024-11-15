---
title: The Surprising Effectiveness of Representation Learning for Visual Imitation
authors:
- Jyothish Pari
- Nur Muhammad Shafiullah
- Sridhar Pandian Arunachalam
- Lerrel Pinto
date: '2021-12-01'
publishDate: '2024-11-15T17:07:01.679261Z'
publication_types:
- manuscript
publication: '*arXiv*'
abstract: 'While visual imitation learning offers one of the most effective ways of
  learning from visual demonstrations, generalizing from them requires either hundreds
  of diverse demonstrations, task specific priors, or large, hard-to-train parametric
  models. One reason such complexities arise is because standard visual imitation
  frameworks try to solve two coupled problems at once: learning a succinct but good
  representation from the diverse visual data, while simultaneously learning to associate
  the demonstrated actions with such representations. Such joint learning causes an
  interdependence between these two problems, which often results in needing large
  amounts of demonstrations for learning. To address this challenge, we instead propose
  to decouple representation learning from behavior learning for visual imitation.
  First, we learn a visual representation encoder from offline data using standard
  supervised and self-supervised learning methods. Once the representations are trained,
  we use non-parametric Locally Weighted Regression to predict the actions. We experimentally
  show that this simple decoupling improves the performance of visual imitation models
  on both offline demonstration datasets and real-robot door opening compared to prior
  work in visual imitation. All of our generated data, code, and robot videos are
  publicly available at https://jyopari.github.io/VINN/.'
tags:
- Computer Science - Robotics
- Computer Science - Computer Vision and Pattern Recognition
- Computer Science - Machine Learning
- Computer Science - Artificial Intelligence
links:
- name: URL
  url: http://arxiv.org/abs/2112.01511
---
