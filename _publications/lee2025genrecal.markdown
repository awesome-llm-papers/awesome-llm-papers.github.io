---
layout: publication
title: 'Genrecal: Generation After Recalibration From Large To Small Vision-language
  Models'
authors: Byung-kwan Lee, Ryo Hachiuma, Yong Man Ro, Yu-chiang Frank Wang, Yueh-hua
  Wu
conference: No Venue
year: 2025
bibkey: lee2025genrecal
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.15681'}]
tags: ["Efficiency", "Model Architecture"]
short_authors: Lee et al.
---
Recent advancements in vision-language models (VLMs) have leveraged large language models (LLMs) to achieve performance on par with closed-source systems like GPT-4V. However, deploying these models in real-world scenarios, particularly on resource-constrained devices, remains challenging due to their substantial computational demands. This has spurred interest in distilling knowledge from large VLMs into smaller, more efficient counterparts. A key challenge arises here from the diversity of VLM architectures, which are built on different LLMs and employ varying token types-differing in vocabulary size, token splits, and token index ordering. To address this challenge of limitation to a specific VLM type, we present Generation after Recalibration (GenRecal), a novel, general-purpose distillation framework for VLMs. GenRecal incorporates a Recalibrator that aligns and adapts feature representations between heterogeneous VLMs, enabling effective knowledge transfer across different types of VLMs. Through extensive experiments on multiple challenging benchmarks, we demonstrate that GenRecal significantly improves baseline performances, eventually outperforming large-scale open- and closed-source VLMs.

https://huggingface.co/discussions/paper/68536fc899bf39f9665c7966