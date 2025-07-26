---
layout: publication
title: Adding Nvme Ssds To Enable And Accelerate 100B Model Fine-tuning On A Single
  GPU
authors: Changyue Liao, Mo Sun, Zihan Yang, Kaiqi Chen, Binhang Yuan, Fei Wu, Zeke
  Wang
conference: No Venue
year: 2024
bibkey: liao2024adding
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2403.06504'}]
tags: ["Efficiency", "Fine-Tuning", "Training Techniques"]
short_authors: Liao et al.
---
Recent advances in large language models have brought immense value to the world, with their superior capabilities stemming from the massive number of parameters they utilize. However, even the GPUs with the highest memory capacities, currently peaking at 80GB, are far from sufficient to accommodate these vast parameters and their associated optimizer states when conducting stochastic gradient descent-based optimization. One approach to hosting such huge models is to aggregate device memory from many GPUs. However, this approach introduces prohibitive costs for most academic researchers, who always have a limited budget for many high-end GPU servers. In this paper, we focus on huge model fine-tuning on a single, even low-end, GPU in a commodity server, which is accessible to most AI researchers. In such a scenario, the state-of-the-art work ZeRO-Infinity suffers from two severe issues when running in a commodity server: 1) low GPU utilization due to inefficient swapping, and 2) limited trainable model size due to CPU memory capacity. The underlying reason is that ZeRO-Infinity is optimized for running on high-end GPU servers. To this end, we present Fuyou, a low-cost training framework that enables efficient 100B huge model fine-tuning on a low-end server with a low-end GPU and limited CPU memory capacity. The key idea is to add the SSD-CPU communication as an optimization dimension and thus carefully co-optimize computation and data swapping from a systematic approach to maximize GPU utilization. The experimental results show that 1) Fuyou is able to fine-tune 175B GPT-3 on a consumer GPU RTX 4090 with high GPU utilization, while ZeRO-Infinity fails to fine-tune; and 2) when training a small GPT-3 13B model, Fuyou achieves 156 TFLOPS on an RTX 4090 GPU while ZeRO-Infinity only achieves 45 TFLOPS.

https://huggingface.co/discussions/paper/65efcd5497074b211656dd24