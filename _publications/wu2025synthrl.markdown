---
layout: publication
title: 'Synthrl: Scaling Visual Reasoning With Verifiable Data Synthesis'
authors: Zijian Wu, Jinjie Ni, Xiangyan Liu, Zichen Liu, Hang Yan, Michael Qizhe Shieh
conference: No Venue
year: 2025
bibkey: wu2025synthrl
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.02096'}]
tags: ["Datasets"]
short_authors: Wu et al.
---
Vision-language models (VLMs) trained via reinforcement learning with verifiable reward (RLVR) have shown notable progress in scaling test-time compute effectively. In this work, we investigate how synthesized RL data can further improve RLVR. To this end, we propose SynthRL-a scalable and guaranteed pipeline for automatic data scaling in reasoning-oriented RL training. SynthRL comprises three key stages: (1) selecting seed questions with appropriate distribution, (2) augmenting them into more challenging variants while preserving the original answers, and (3) a guaranteed verification stage that ensures near-perfect correctness and difficulty enhancement. Our empirical experiments demonstrate SynthRL's scalability and effectiveness. When applied to the MMK12 dataset, SynthRL synthesizes over 3.3K additional verifiable, challenging questions from approximately 8K seed samples. Models trained with our synthesized data achieve consistent gains across five out-of-domain visual math reasoning benchmarks, with a significant improvement over baseline models trained on seed data alone. Notably, detailed analysis reveals that the gains are more pronounced on the most challenging evaluation samples, highlighting SynthRL's effectiveness in eliciting deeper and more complex reasoning patterns.

https://huggingface.co/discussions/paper/683fa3707ed99d0040761154