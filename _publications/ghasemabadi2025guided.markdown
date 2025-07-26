---
layout: publication
title: 'Guided By Gut: Efficient Test-time Scaling With Reinforced Intrinsic Confidence'
authors: Amirhosein Ghasemabadi, Keith G. Mills, Baochun Li, di Niu
conference: No Venue
year: 2025
bibkey: ghasemabadi2025guided
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2505.20325'}]
tags: ["Reinforcement Learning"]
short_authors: Ghasemabadi et al.
---
Test-Time Scaling (TTS) methods for enhancing Large Language Model (LLM) reasoning often incur substantial computational costs, primarily due to extensive reliance on external Process Reward Models (PRMs) or sampling methods like Best-of-N (BoN). This paper introduces Guided by Gut (GG), an efficient self-guided TTS framework that achieves PRM-level performance without costly external verifier models. Our method employs a lightweight tree search guided solely by intrinsic LLM signals, token-level confidence and step novelty. One critical innovation is improving the reliability of internal confidence estimates via a targeted reinforcement learning fine-tuning phase. Empirical evaluations on challenging mathematical reasoning benchmarks demonstrate that GG enables smaller models (e.g., 1.5B parameters) to achieve accuracy matching or surpassing significantly larger models (e.g., 32B-70B parameters), while reducing GPU memory usage by up to 10x. Compared to PRM-based methods, GG achieves comparable accuracy with 8x faster inference speeds and 4-5x lower memory usage. Additionally, GG reduces KV cache memory usage by approximately 50% compared to the BoN strategy, facilitating more efficient and practical deployment of TTS techniques.

https://huggingface.co/discussions/paper/6836abd7871c9d398c136f12