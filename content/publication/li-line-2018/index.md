---
title: On-Line Temperature Estimation for Noisy Thermal Sensors Using a Smoothing
  Filter-Based Kalman Predictor
authors:
- Xin Li
- Xingtao Ou
- Zhi Li
- Henglu Wei
- Wei Zhou
- Zhemin Duan
date: '2018-02-01'
publishDate: '2024-11-15T17:07:02.194909Z'
publication_types:
- article-journal
publication: '*Sensors (Basel, Switzerland)*'
doi: 10.3390/s18020433
abstract: Dynamic thermal management (DTM) mechanisms utilize embedded thermal sensors
  to collect fine-grained temperature information for monitoring the real-time thermal
  behavior of multi-core processors. However, embedded thermal sensors are very susceptible
  to a variety of sources of noise, including environmental uncertainty and process
  variation. This causes the discrepancies between actual temperatures and those observed
  by on-chip thermal sensors, which seriously affect the efficiency of DTM. In this
  paper, a smoothing filter-based Kalman prediction technique is proposed to accurately
  estimate the temperatures from noisy sensor readings. For the multi-sensor estimation
  scenario, the spatial correlations among different sensor locations are exploited.
  On this basis, a multi-sensor synergistic calibration algorithm (known as MSSCA)
  is proposed to improve the simultaneous prediction accuracy of multiple sensors.
  Moreover, an infrared imaging-based temperature measurement technique is also proposed
  to capture the thermal traces of an advanced micro devices (AMD) quad-core processor
  in real time. The acquired real temperature data are used to evaluate our prediction
  performance. Simulation shows that the proposed synergistic calibration scheme can
  reduce the root-mean-square error (RMSE) by 1.2 ∘C and increase the signal-to-noise
  ratio (SNR) by 15.8 dB (with a very small average runtime overhead) compared with
  assuming the thermal sensor readings to be ideal. Additionally, the average false
  alarm rate (FAR) of the corrected sensor temperature readings can be reduced by
  28.6%. These results clearly demonstrate that if our approach is used to perform
  temperature estimation, the response mechanisms of DTM can be triggered to adjust
  the voltages, frequencies, and cooling fan speeds at more appropriate times.
links:
- name: URL
  url: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5855121/
---
