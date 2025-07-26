---
layout: publication
title: 'STAR: Spatial-temporal Augmentation With Text-to-video Models For Real-world
  Video Super-resolution'
authors: Rui Xie, Yinhong Liu, Penghao Zhou, Chen Zhao, Jun Zhou, Kai Zhang, Zhenyu
  Zhang, Jian Yang, Zhenheng Yang, Ying Tai
conference: No Venue
year: 2025
bibkey: xie2025star
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2501.02976'}]
tags: ["Datasets", "Time Series"]
short_authors: Xie et al.
---
Image diffusion models have been adapted for real-world video super-resolution to tackle over-smoothing issues in GAN-based methods. However, these models struggle to maintain temporal consistency, as they are trained on static images, limiting their ability to capture temporal dynamics effectively. Integrating text-to-video (T2V) models into video super-resolution for improved temporal modeling is straightforward. However, two key challenges remain: artifacts introduced by complex degradations in real-world scenarios, and compromised fidelity due to the strong generative capacity of powerful T2V models (e.g., CogVideoX-5B). To enhance the spatio-temporal quality of restored videos, we introduce~\name (Spatial-Temporal Augmentation with T2V models for Real-world video super-resolution), a novel approach that leverages T2V models for real-world video super-resolution, achieving realistic spatial details and robust temporal consistency. Specifically, we introduce a Local Information Enhancement Module (LIEM) before the global attention block to enrich local details and mitigate degradation artifacts. Moreover, we propose a Dynamic Frequency (DF) Loss to reinforce fidelity, guiding the model to focus on different frequency components across diffusion steps. Extensive experiments demonstrate~\name~outperforms state-of-the-art methods on both synthetic and real-world datasets.

https://huggingface.co/discussions/paper/677c986e1b9a7499c3644fb5