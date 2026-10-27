---
list_summary: "Neuro-inspired fingertip force estimation from a single IMU ring and EMG channel."
title: 'Trading Sensing for Structure: Sparse IMU-EMG Fingertip Force Estimation via Neuro-inspired Structured Modeling'
authors:
- Yang Gao
- Yingjing Xiao
- Junbin Ren
- Chenxu Zhang
- Wenbo Zhang
- Zhanpeng Jin
author_notes:
- ''
- ''
- ''
- ''
- ''
- ''
date: '2026-09-26'
publishDate: '2026-09-26T00:00:00+08:00'
publication_priority: 1
hide_date: true
show_date_updated: false
reading_time: false
publication_types:
- paper-conference
publication: '*NeurIPS 2026, Main Track* (accepted; Poster)'
abstract: >-
  We present NiSM, a neuro-inspired structured model that estimates per-finger contact forces during grasping using a minimal wearable configuration: a thumb-mounted IMU ring and a single-channel wrist EMG watch. The work investigates how far structural inductive biases can compensate for missing information as sensing density decreases. Inspired by the intention–planning–execution stages of human sensorimotor control, NiSM first derives grasp context from an IMU-inferred latent hand-shape representation. It then uses conditional BatchNorm to modulate thumb-motion features with this context and an L1-sparse feature-to-finger mapping to generate base pressures resembling finger synergies. Finally, EMG features produce per-finger gains that are multiplied with the base pressures and a context mask to obtain the output. We collect and release a dataset spanning 20 participants, 16 objects, and more than one million frames, and also evaluate the model on the public PiMForce dataset. With only 1.71M parameters, NiSM performs best among sparse-input baselines. On PiMForce, it achieves an R² of 54.4% and a Pearson correlation coefficient of 76.6%, slightly outperforming a dense model with 66.39M parameters that uses eight-channel EMG and 3D hand poses. Performance also degrades more gradually as the number of training users decreases. Ablation studies show that all three structural priors contribute, with EMG gain modulation having the largest effect. Limitations include estimating only normal pressure rather than three-dimensional force, dependence on IMU-to-hand-shape inference for context quality, and the need to validate long-term wear and open-world performance.
tags:
- NeurIPS
- Fingertip Force Estimation
- IMU
- EMG
- Wearable Computing
thumbnail_alt: "NiSM maps grasp intention, planning, and execution to structured fingertip force estimation using IMU and sEMG signals."
image:
  caption: "Overview of the neuro-inspired structured model (NiSM)."
  alt_text: "NiSM maps grasp intention, planning, and execution to structured fingertip force estimation using IMU and sEMG signals."
  preview_only: false
---
