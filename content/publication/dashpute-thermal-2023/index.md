---
title: 'Thermal Spread Functions (TSF): Physics-Guided Material Classification'
authors:
- Aniket Dashpute
- Vishwanath Saragadam
- Emma Alexander
- Florian Willomitzer
- Aggelos Katsaggelos
- Ashok Veeraraghavan
- Oliver Cossairt
date: '2023-06-01'
publishDate: '2024-11-15T17:07:02.634213Z'
publication_types:
- paper-conference
publication: '*2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition
  (CVPR)*'
doi: 10.1109/CVPR52729.2023.00164
abstract: Robust and non-destructive material classification is a challenging but
  crucial first-step in numerous vision applications. We propose a physics-guided
  material classification framework that relies on thermal properties of the object.
  Our key observation is that the rate of heating and cooling of an object depends
  on the unique intrinsic properties of the material, namely the emissivity and diffusivity.
  We leverage this observation by gently heating the objects in the scene with a low-power
  laser for a fixed duration and then turning it off, while a thermal camera captures
  measurements during the heating and cooling process. We then take this spatial and
  temporal “thermal spread function” (TSF) to solve an inverse heat equation using
  the finite-differences approach, resulting in a spatially varying estimate of diffusivity
  and emissivity. These tuples are then used to train a classifier that produces a
  fine-grained material label at each spatial pixel. Our approach is extremely simple
  requiring only a small light source (low power laser) and a thermal camera, and
  produces robust classification results with 86% accuracy over 16 classes1.
links:
- name: URL
  url: https://ieeexplore.ieee.org/document/10204899/
---
