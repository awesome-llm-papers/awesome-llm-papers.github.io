---
layout: publication
title: 'Alphaone: Reasoning Models Thinking Slow And Fast At Test Time'
authors: Junyu Zhang, Runpei Dong, Han Wang, Xuying Ning, Haoran Geng, Peihao Li,
  Xialin He, Yutong Bai, Jitendra Malik, Saurabh Gupta, Huan Zhang
conference: No Venue
year: 2025
bibkey: zhang2025alphaone
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2505.24863'}]
tags: ["Efficiency", "Has Code", "Tools"]
short_authors: Zhang et al.
---
This paper presents AlphaOne (alpha1), a universal framework for modulating reasoning progress in large reasoning models (LRMs) at test time. alpha1 first introduces alpha moment, which represents the scaled thinking phase with a universal parameter alpha. Within this scaled pre-alpha moment phase, it dynamically schedules slow thinking transitions by modeling the insertion of reasoning transition tokens as a Bernoulli stochastic process. After the alpha moment, alpha1 deterministically terminates slow thinking with the end-of-thinking token, thereby fostering fast reasoning and efficient answer generation. This approach unifies and generalizes existing monotonic scaling methods by enabling flexible and dense slow-to-fast reasoning modulation. Extensive empirical studies on various challenging benchmarks across mathematical, coding, and scientific domains demonstrate alpha1's superior reasoning capability and efficiency. Project page: https://alphaone-project.github.io/

https://huggingface.co/discussions/paper/683d0b3ee2a7d8d9778bd1ce