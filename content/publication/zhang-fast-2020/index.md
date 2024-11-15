---
title: Fast computation of soft tissue thermal response under deformation based on
  fast explicit dynamics finite element algorithm for surgical simulation
authors:
- Jinao Zhang
- Sunita Chauhan
date: '2020-04-01'
publishDate: '2024-11-15T17:07:02.598524Z'
publication_types:
- article-journal
publication: '*Computer Methods and Programs in Biomedicine*'
doi: 10.1016/j.cmpb.2019.105244
abstract: Background and objectives During thermal heating surgical procedures such
  as electrosurgery, thermal ablative treatment and hyperthermia, soft tissue deformation
  due to surgical tool-tissue interaction and patient movement can affect the distribution
  of thermal energy induced. Soft tissue temperature must be obtained from the deformed
  tissue for precise delivery of thermal energy. However, the classical Pennes bio-heat
  transfer model can handle only the static non-moving state of tissue. In addition,
  in order to enable a surgeon to visualise the simulated results immediately, the
  solution procedure must be suitable for real-time thermal applications. Methods
  This paper presents a formulation of bio-heat transfer under the effect of soft
  tissue deformation for fast or near real-time tissue temperature prediction, based
  on fast explicit dynamics finite element algorithm (FED-FEM) for transient heat
  transfer. The proposed thermal analysis under deformation is achieved by transformation
  of the unknown deformed tissue state to the known initial static state via a mapping
  function. The appropriateness and effectiveness of the proposed formulation are
  evaluated on a realistic virtual human liver model with blood vessels to demonstrate
  a clinically relevant scenario of thermal ablation of hepatic cancer. Results For
  numerical accuracy, the proposed formulation can achieve a typical 10−3 level of
  normalised relative error at nodes and between 10−4 and 10−5 level of total errors
  for the simulation, by comparing solutions against the commercial finite element
  analysis package. For computation time, the proposed formulation under tissue deformation
  with anisotropic temperature-dependent properties consumes 2.518 × 10−4 ms for one
  element thermal loads computation, compared to 2.237 × 10−4 ms for the formulation
  without deformation which is 0.89 times of the former. Comparisons with three other
  formulations for isotropic and temperature-independent properties are also presented.
  Conclusions Compared to conventional methods focusing on numerical accuracy, convergence
  and stability, the proposed formulation focuses on computational performance for
  fast tissue thermal analysis. Compared to the classical Pennes model that handles
  only the static state of tissue, the proposed formulation can achieve fast thermal
  analysis on deformed states of tissue and can be applied in addition to tissue deformable
  models for non-linear heating analysis at even large deformation of soft tissue,
  leading to great translational potential in dynamic tissue temperature analysis
  and thermal dosimetry computation for computer-integrated medical education and
  personalised treatment.
tags:
- Bio-heat transfer
- Surgical simulation
- Explicit dynamics finite element
- Non-linear computational analysis
- Soft tissue deformation
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0169260719311344
---
