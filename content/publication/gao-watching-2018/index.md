---
title: 'Watching and Safeguarding Your 3D Printer: Online Process Monitoring Against
  Cyber-Physical Attacks'
authors:
- Yang Gao
- Borui Li
- Wei Wang
- Wenyao Xu
- Chi Zhou
- Zhanpeng Jin
date: '2018-09-01'
publishDate: '2025-07-06T09:47:45.955481Z'
publication_types:
- article-journal
publication: '*Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies (PACM IMWUT / UbiComp)*'
doi: 10.1145/3264918
abstract: The increasing adoption of 3D printing in many safety and mission critical
  applications exposes 3D printers to a variety of cyber attacks that may result in
  catastrophic consequences if the printing process is compromised. For example, the
  mechanical properties (e.g., physical strength, thermal resistance, dimensional
  stability) of 3D printed objects could be significantly affected and degraded if
  a simple printing setting is maliciously changed. To address this challenge, this
  study proposes a model-free real-time online process monitoring approach that is
  capable of detecting and defending against the cyber-physical attacks on the firmwares
  of 3D printers. Specifically, we explore the potential attacks and consequences
  of four key printing attributes (including infill path, printing speed, layer thickness,
  and fan speed) and then formulate the attack models. Based on the intrinsic relation
  between the printing attributes and the physical observations, our defense model
  is established by systematically analyzing the multi-faceted, real-time measurement
  collected from the accelerometer, magnetometer and camera. The Kalman filter and
  Canny filter are used to map and estimate three aforementioned critical toolpath
  information that might affect the printing quality. Mel-frequency Cepstrum Coefficients
  are used to extract features for fan speed estimation. Experimental results show
  that, for a complex 3D printed design, our method can achieve 4% Hausdorff distance
  compared with the model dimension for infill path estimate, 6.07% Mean Absolute
  Percentage Error (MAPE) for speed estimate, 9.57% MAPE for layer thickness estimate,
  and 96.8% accuracy for fan speed identification. Our study demonstrates that, this
  new approach can effectively defend against the cyber-physical attacks on 3D printers
  and 3D printing process.
links:
- name: URL
  url: https://dl.acm.org/doi/10.1145/3264918
---
