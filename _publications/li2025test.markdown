---
layout: publication
title: 'Test-time Preference Optimization: On-the-fly Alignment Via Iterative Textual
  Feedback'
authors: Yafu Li, Xuyang Hu, Xiaoye Qu, Linjie Li, Yu Cheng
conference: No Venue
year: 2025
bibkey: li2025test
additional_links: [{name: Code, url: 'https://github.com/yafuly/TPO'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/6791c6409e215712a7d4bc23'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2501.12895'}]
tags: ["Efficiency", "Has Code", "Reinforcement Learning"]
short_authors: Li et al.
---
Large language models (LLMs) demonstrate impressive performance but lack the flexibility to adapt to human preferences quickly without retraining. In this work, we introduce Test-time Preference Optimization (TPO), a framework that aligns LLM outputs with human preferences during inference, removing the need to update model parameters. Rather than relying on purely numerical rewards, TPO translates reward signals into textual critiques and uses them as textual rewards to iteratively refine its response. Evaluations on benchmarks covering instruction following, preference alignment, safety, and mathematics reveal that TPO progressively improves alignment with human preferences. Notably, after only a few TPO steps, the initially unaligned Llama-3.1-70B-SFT model can surpass the aligned counterpart, Llama-3.1-70B-Instruct. Furthermore, TPO scales efficiently with both the search width and depth during inference. Through case studies, we illustrate how TPO exploits the innate capacity of LLM to interpret and act upon reward signals. Our findings establish TPO as a practical, lightweight alternative for test-time preference optimization, achieving alignment on the fly. Our code is publicly available at https://github.com/yafuly/TPO.

https://huggingface.co/discussions/paper/6791c6409e215712a7d4bc23