---
title: Feasibility Analyses of Real-Time Detection of Wildlife Using UAV-Derived Thermal
  and RGB Images
authors:
- Seunghyeon Lee
- Youngkeun Song
- Sung-Ho Kil
date: '2021-01-01'
publishDate: '2024-11-15T17:07:02.399155Z'
publication_types:
- article-journal
publication: '*Remote Sensing*'
doi: 10.3390/rs13112169
abstract: Wildlife monitoring is carried out for diverse reasons, and monitoring methods
  have gradually advanced through technological development. Direct field investigations
  have been replaced by remote monitoring methods, and unmanned aerial vehicles (UAVs)
  have recently become the most important tool for wildlife monitoring. Many previous
  studies on detecting wild animals have used RGB images acquired from UAVs, with
  most of the analyses depending on machine learning–deep learning (ML–DL) methods.
  These methods provide relatively accurate results, and when thermal sensors are
  used as a supplement, even more accurate detection results can be obtained through
  complementation with RGB images. However, because most previous analyses were based
  on ML–DL methods, a lot of time was required to generate training data and train
  detection models. This drawback makes ML–DL methods unsuitable for real-time detection
  in the field. To compensate for the disadvantages of the previous methods, this
  paper proposes a real-time animal detection method that generates a total of six
  applicable input images depending on the context and uses them for detection. The
  proposed method is based on the Sobel edge algorithm, which is simple but can detect
  edges quickly based on change values. The method can detect animals in a single
  image without training data. The fastest detection time per image was 0.033 s, and
  all frames of a thermal video could be analyzed. Furthermore, because of the synchronization
  of the properties of the thermal and RGB images, the performance of the method was
  above average in comparison with previous studies. With target images acquired at
  heights below 100 m, the maximum detection precision and detection recall of the
  most accurate input image were 0.804 and 0.699, respectively. However, the low resolution
  of the thermal sensor and its shooting height limitation were hindrances to wildlife
  detection. The aim of future research will be to develop a detection method that
  can improve these shortcomings.
tags:
- instant and automated detection
- mixed image analysis
- multiple height shooting
- object-based animal detection
- thermal sensing
- unmanned aerial vehicle
- wildlife monitoring
links:
- name: URL
  url: https://www.mdpi.com/2072-4292/13/11/2169
---
