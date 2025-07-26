---
layout: publication
title: 'Less-to-more Generalization: Unlocking More Controllability By In-context
  Generation'
authors: Shaojin Wu, Mengqi Huang, Wenxu Wu, Yufeng Cheng, Fei Ding, Qian He
conference: No Venue
year: 2025
bibkey: wu2025less
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2504.02160'}]
tags: ["Applications", "Datasets"]
short_authors: Wu et al.
---
Although subject-driven generation has been extensively explored in image generation due to its wide applications, it still has challenges in data scalability and subject expansibility. For the first challenge, moving from curating single-subject datasets to multiple-subject ones and scaling them is particularly difficult. For the second, most recent methods center on single-subject generation, making it hard to apply when dealing with multi-subject scenarios. In this study, we propose a highly-consistent data synthesis pipeline to tackle this challenge. This pipeline harnesses the intrinsic in-context generation capabilities of diffusion transformers and generates high-consistency multi-subject paired data. Additionally, we introduce UNO, which consists of progressive cross-modal alignment and universal rotary position embedding. It is a multi-image conditioned subject-to-image model iteratively trained from a text-to-image model. Extensive experiments show that our method can achieve high consistency while ensuring controllability in both single-subject and multi-subject driven generation.

https://huggingface.co/discussions/paper/67efd1d140e0a904109cad62