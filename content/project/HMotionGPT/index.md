---
title: "HMotionGPT: Aligning Hand Motions and Natural Language for Activity Understanding with Smart Rings"
summary: "An open-source multimodal framework that aligns smart-ring IMU signals with natural language for hand-centric activity understanding."
date: 2026-04-07
tags:
  - Open Source
  - Wearable Computing
  - Human Activity Recognition
  - Multimodal LLM
  - Smart Rings
image:
  caption: "HMotionGPT aligns hand-motion signals captured by smart rings with natural language."
authors:
  - admin
---

## Project Overview

**HMotionGPT** is an open-source multimodal framework that bridges smart-ring inertial measurement unit (IMU) signals and natural language for hand-centric activity understanding. By aligning motion representations with a language model, HMotionGPT supports downstream tasks including activity classification, motion captioning, and instruction-following activity understanding.

The project accompanies our paper, **HMotionGPT: Aligning Hand Motions and Natural Language for Activity Understanding with Smart Rings**, published in **Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies (PACM IMWUT / UbiComp 2026)**.

## Open-Source Release

The public repository provides the core model construction and training pipeline under the MIT License, including:

- Stage-1 alignment training for the IMU projector
- Stage-2 supervised fine-tuning with a frozen projector
- Configurable language-model backbones
- Minimal runnable examples for smoke testing

## Key Contributions

### Motion-Language Alignment

HMotionGPT converts hand-motion sequences captured by smart rings into representations that can be aligned with a large language model, connecting wearable sensing with flexible natural-language reasoning.

### Two-Stage Training Pipeline

The framework first trains an IMU projector while freezing the language model, then performs supervised fine-tuning to improve instruction following and task-specific generation.

### Hand-Centric Activity Understanding

The aligned model supports several forms of activity understanding, from recognizing actions to producing natural-language descriptions of hand-object interactions.

## Resources

- **Open-Source Code:** [SCUT-HAI/HMotionGPT on GitHub](https://github.com/SCUT-HAI/HMotionGPT)
- **Paper:** [ACM Digital Library](https://dl.acm.org/doi/10.1145/3810222)
- **License:** [MIT License](https://github.com/SCUT-HAI/HMotionGPT/blob/main/LICENSE)
