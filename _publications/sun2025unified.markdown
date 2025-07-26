---
layout: publication
title: Unified Continuous Generative Models
authors: Peng Sun, Yi Jiang, Tao Lin
conference: No Venue
year: 2025
bibkey: sun2025unified
additional_links: [{name: Code, url: 'https://github.com/LINs-lab/UCGM'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/6822c7d98fc623ca8c6b260c'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2505.07447'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Peng Sun, Yi Jiang, Tao Lin
---
Recent advances in continuous generative models, including multi-step approaches like diffusion and flow-matching (typically requiring 8-1000 sampling steps) and few-step methods such as consistency models (typically 1-8 steps), have demonstrated impressive generative performance. However, existing work often treats these approaches as distinct paradigms, resulting in separate training and sampling methodologies. We introduce a unified framework for training, sampling, and analyzing these models. Our implementation, the Unified Continuous Generative Models Trainer and Sampler (UCGM-\{T,S\}), achieves state-of-the-art (SOTA) performance. For example, on ImageNet 256x256 using a 675M diffusion transformer, UCGM-T trains a multi-step model achieving 1.30 FID in 20 steps and a few-step model reaching 1.42 FID in just 2 steps. Additionally, applying UCGM-S to a pre-trained model (previously 1.26 FID at 250 steps) improves performance to 1.06 FID in only 40 steps. Code is available at: https://github.com/LINs-lab/UCGM.

https://huggingface.co/discussions/paper/6822c7d98fc623ca8c6b260c