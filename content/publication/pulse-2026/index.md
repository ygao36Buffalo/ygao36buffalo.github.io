---
hide_list_abstract: true
title: 'PULSE: A Synchronized Five-Modality Dataset for Sensorimotor Coordination in Long-Horizon Daily Activities'
authors:
- Wolin Liang
- Yang Gao
- Peiyu Yan
- YueXiang Hu
- Yingjing Xiao
- Xiongfeng Ying
- YingNian Guo
- Cheng Zhang
- Zhanpeng Jin
corresponding_authors:
- Yang Gao
author_notes:
- ''
- ''
- ''
- ''
- ''
- ''
- ''
- ''
- ''
date: '2026-09-26'
publishDate: '2026-09-26T00:00:00+08:00'
publication_priority: 2
hide_date: true
show_date_updated: false
reading_time: false
publication_types:
- paper-conference
publication: '*NeurIPS 2026, Evaluations and Datasets Track* (accepted; **Spotlight**)'
awards:
- Spotlight
abstract: >-
  Research on motor control shows that gaze, muscle activation, and tactile feedback are closely coupled in daily activities: the eyes often fixate on the next target before the hand arrives, and electromyographic activation precedes grip-force production by hundreds of milliseconds. However, existing human activity datasets typically cover only one or two sensing modalities and focus on short, isolated actions, limiting the evaluation of temporal cross-modal sensorimotor learning in long-horizon compositional tasks. We introduce PULSE (Physiological Unified Long-duration Synchronized Embodiment), a five-modality dataset collected with 100 Hz hardware synchronization: full-body optical motion capture including finger-joint motion, surface electromyography (sEMG), binocular eye tracking, wearable inertial measurement units (IMUs), and finger-level pressure arrays measuring quantitative grip force. The dataset includes 40 participants performing eight everyday scenarios, such as desk organization, parcel packing, and post-meal table clearing. Each scenario recording captures the continuous execution of a complete task, supplemented by a set of motion-primitive recordings. Of 304 task recordings (approximately 7.0 hours), 282 are densely annotated with 7,789 action segments, each labeled with a motion primitive, the hand used, the manipulated object, and a natural-language description with four paraphrases. We establish benchmarks for scenario and fine-grained action recognition, grasp-onset anticipation, robustness to missing modalities, tactile-driven grasp-state recognition, and cross-modal pressure prediction. We evaluate three backbone networks, nine fusion strategies, seven published baseline models, and task-specific models including SyncFuse and DailyActFormer. No single modality dominates across tasks: when used alone, sEMG performs best for grasp anticipation, whereas IMUs perform best for scenario recognition. Multimodal fusion remains challenging at the current data scale, leaving substantial room for improvement across benchmarks. The data, annotations, and baseline code are publicly available.
tags:
- NeurIPS
- Dataset
- Multimodal Sensing
- Sensorimotor Coordination
- Wearable Computing
thumbnail_alt: "PULSE five-modality sensing setup with motion capture, sEMG, gaze tracking, IMUs, and finger-level pressure sensors."
image:
  caption: "PULSE data collection setup."
  alt_text: "PULSE five-modality sensing setup with motion capture, sEMG, gaze tracking, IMUs, and finger-level pressure sensors."
  preview_only: false
---
