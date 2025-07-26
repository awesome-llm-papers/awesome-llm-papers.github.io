---
layout: publication
title: LOGO -- Long Context Alignment Via Efficient Preference Optimization
authors: Zecheng Tang, Zechen Sun, Juntao Li, Qiaoming Zhu, Min Zhang
conference: No Venue
year: 2024
bibkey: tang2024logo
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2410.18533'}]
tags: ["Efficiency", "Memory & Context"]
short_authors: Tang et al.
---
Long-context models(LCMs) have shown great potential in processing long input sequences(even more than 100M tokens) conveniently and effectively. With significant progress, recent research has pointed out that LCMs can accurately locate token-level salient information within the context. Yet, the generation performance of these LCMs is far from satisfactory and might result in misaligned responses, such as hallucinations. To enhance the generation capability of LCMs, existing works have investigated the effects of data size and quality for both pre-training and instruction tuning. Though achieving meaningful improvement, previous methods fall short in either effectiveness or efficiency. In this paper, we introduce LOGO(Long cOntext aliGnment via efficient preference Optimization), a training strategy that first introduces preference optimization for long-context alignment. To overcome the GPU memory-bound issue caused by the long sequence, LOGO employs a reference-free preference optimization strategy and adopts a position synthesis method to construct the training data. By training with only 0.3B data on a single 8timesA800 GPU machine for 16 hours, LOGO allows the Llama-3-8B-Instruct-80K model to achieve comparable performance with GPT-4 in real-world long-context tasks while preserving the model's original capabilities on other tasks, e.g., language modeling and MMLU. Moreover, LOGO can extend the model's context window size while enhancing its generation performance.

https://huggingface.co/discussions/paper/671b0a2fa9a89705ec15a31d