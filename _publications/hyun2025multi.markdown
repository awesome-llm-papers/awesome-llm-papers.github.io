---
layout: publication
title: Multi-granular Spatio-temporal Token Merging For Training-free Acceleration
  Of Video Llms
authors: Jeongseok Hyun, Sukjun Hwang, Su Ho Han, Taeoh Kim, Inwoong Lee, Dongyoon
  Wee, Joon-young Lee, Seon Joo Kim, Minho Shim
conference: No Venue
year: 2025
bibkey: hyun2025multi
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2507.07990'}]
tags: ["Training Techniques"]
short_authors: Hyun et al.
---
Video large language models (LLMs) achieve strong video understanding by leveraging a large number of spatio-temporal tokens, but suffer from quadratic computational scaling with token count. To address this, we propose a training-free spatio-temporal token merging method, named STTM. Our key insight is to exploit local spatial and temporal redundancy in video data which has been overlooked in prior work. STTM first transforms each frame into multi-granular spatial tokens using a coarse-to-fine search over a quadtree structure, then performs directed pairwise merging across the temporal dimension. This decomposed merging approach outperforms existing token reduction methods across six video QA benchmarks. Notably, STTM achieves a 2times speed-up with only a 0.5% accuracy drop under a 50% token budget, and a 3times speed-up with just a 2% drop under a 30% budget. Moreover, STTM is query-agnostic, allowing KV cache reuse across different questions for the same video. The project page is available at https://www.jshyun.me/projects/sttm.

https://huggingface.co/discussions/paper/68708157c8391850d6097872