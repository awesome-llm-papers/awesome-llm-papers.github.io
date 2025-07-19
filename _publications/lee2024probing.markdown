---
layout: publication
title: 'Probing LLM Hallucination From Within: Perturbation-driven Approach Via Internal
  Knowledge'
authors: Lee et al.
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2023'
year: 2024
bibkey: lee2024probing
citations: 92
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2411.09689'}]
tags: [Prompting, Fine Tuning, Training Techniques, ACL, EMNLP, Applications, Datasets]
---
LLM hallucination, where unfaithful text is generated, presents a critical challenge for LLMs' practical applications. Current detection methods often resort to external knowledge, LLM fine-tuning, or supervised training with large hallucination-labeled datasets. Moreover, these approaches do not distinguish between different types of hallucinations, which is crucial for enhancing detection performance. To address such limitations, we introduce hallucination probing, a new task that classifies LLM-generated text into three categories: aligned, misaligned, and fabricated. Driven by our novel discovery that perturbing key entities in prompts affects LLM's generation of these three types of text differently, we propose SHINE, a novel hallucination probing method that does not require external knowledge, supervised training, or LLM fine-tuning. SHINE is effective in hallucination probing across three modern LLMs, and achieves state-of-the-art performance in hallucination detection, outperforming seven competing methods across four datasets and four LLMs, underscoring the importance of probing for accurate detection.