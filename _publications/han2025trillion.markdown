---
layout: publication
title: Trillion 7B Technical Report
authors: Sungjun Han, Juyoung Suk, Suyeong An, Hyungguk Kim, Kyuseok Kim, Wonsuk Yang,
  Seungtaek Choi, Jamin Shin
conference: No Venue
year: 2025
bibkey: han2025trillion
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2504.15431'}]
tags: ["Training Techniques"]
short_authors: Han et al.
---
We introduce Trillion-7B, the most token-efficient Korean-centric multilingual LLM available. Our novel Cross-lingual Document Attention (XLDA) mechanism enables highly efficient and effective knowledge transfer from English to target languages like Korean and Japanese. Combined with optimized data mixtures, language-specific filtering, and tailored tokenizer construction, Trillion-7B achieves competitive performance while dedicating only 10% of its 2T training tokens to multilingual data and requiring just 59.4K H100 GPU hours (\$148K) for full training. Comprehensive evaluations across 27 benchmarks in four languages demonstrate Trillion-7B's robust multilingual performance and exceptional cross-lingual consistency.

https://huggingface.co/discussions/paper/680879ebd6dc8bf64565c9bb