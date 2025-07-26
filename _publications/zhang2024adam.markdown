---
layout: publication
title: 'Adam-mini: Use Fewer Learning Rates To Gain More'
authors: Yushun Zhang, Congliang Chen, Ziniu Li, Tian Ding, Chenwei Wu, Yinyu Ye,
  Zhi-quan Luo, Ruoyu Sun
conference: No Venue
year: 2024
bibkey: zhang2024adam
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2406.16793'}]
tags: ["Fine-Tuning", "Training Techniques"]
short_authors: Zhang et al.
---
We propose Adam-mini, an optimizer that achieves on-par or better performance than AdamW with 45% to 50% less memory footprint. Adam-mini reduces memory by cutting down the learning rate resources in Adam (i.e., 1/v). We find that geq 90% of these learning rates in v could be harmlessly removed if we (1) carefully partition the parameters into blocks following our proposed principle on Hessian structure; (2) assign a single but good learning rate to each parameter block. We further find that, for each of these parameter blocks, there exists a single high-quality learning rate that can outperform Adam, provided that sufficient resources are available to search it out. We then provide one cost-effective way to find good learning rates and propose Adam-mini. Empirically, we verify that Adam-mini performs on par or better than AdamW on various language models sized from 125M to 7B for pre-training, supervised fine-tuning, and RLHF. The reduced memory footprint of Adam-mini also alleviates communication overheads among GPUs and CPUs, thereby increasing throughput. For instance, Adam-mini achieves 49.6% higher throughput than AdamW when pre-training Llama2-7B on 2times A800-80GB GPUs, which saves 33% wall-clock time for pre-training.

https://huggingface.co/discussions/paper/667cd8a77bd463a39081122e