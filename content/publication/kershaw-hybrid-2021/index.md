---
title: Hybrid machine learning-enabled adaptive welding speed control
authors:
- Joseph Kershaw
- Rui Yu
- YuMing Zhang
- Peng Wang
date: '2021-11-01'
publishDate: '2024-11-15T17:07:02.528660Z'
publication_types:
- article-journal
publication: '*Journal of Manufacturing Processes*'
doi: 10.1016/j.jmapro.2021.09.023
abstract: Industrial robots have become more diverse and common for automating manufacturing
  processes, such as welding. Existing robotic control, however, is incapable of adaptively
  adjusting its operation in response to a dynamic welding environment, whereas a
  skilled human welder can. Sophisticated and adaptive robotic control relies on the
  effective and efficient processing of perception data, characterization and prediction
  of highly dynamic systems, and real-time adaptative robotic reactions. This research
  presents a preliminary study on developing appropriate Machine Learning (ML) techniques
  for real-time welding quality prediction and adaptive welding speed adjustment for
  GTAW welding at a constant current. In order to collect the data needed to train
  the hybrid ML models, two cameras are applied to monitor the welding process, with
  one camera (available in practical robotic welding) recording the top-side weld
  pool dynamics and a second camera (unavailable in practical robotic welding, but
  applicable for training purpose) recording the back-side bead formation. Given these
  two data sets, correlations can be discovered through a convolutional neural network
  (CNN) that is good at image characterization. With the CNN, top-side weld pool images
  can be analyzed to predict the back-side bead width during active welding control.
  Furthermore, the monitoring process has been applied to multiple experimental trials
  with varying speeds. This allowed the effect of welding speed on bead width to be
  modeled through a Multi-Layer Perceptron (MLP). Through the trained MLP, a computationally
  efficient gradient descent algorithm has been developed to adjust the travel speed
  accordingly to achieve an optimal bead width with full material penetration. Because
  of the nature of gradient descent, the robot would change faster when the quality
  is further away and then fine-tune the speed when it was close to the goal. Experimental
  studies have shown promising results on real-time bead width prediction and adaptive
  speed adjustment to realize ideal bead width.
tags:
- Machine learning
- Adaptive control
- Convolutional neural network
- Gradient descent
- Robotic welding
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S1526612521006745
---
