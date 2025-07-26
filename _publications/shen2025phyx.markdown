---
layout: publication
title: 'Phyx: Does Your Model Have The "wits" For Physical Reasoning?'
authors: Hui Shen, Taiqiang Wu, Qi Han, Yunta Hsieh, Jizhou Wang, Yuyue Zhang, Yuxin
  Cheng, Zijian Hao, Yuansheng Ni, Xin Wang, Zhongwei Wan, Kai Zhang, Wendong Xu,
  Jing Xiong, Ping Luo, Wenhu Chen, Chaofan Tao, Zhuoqing Mao, Ngai Wong
conference: No Venue
year: 2025
bibkey: shen2025phyx
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2505.15929'}]
tags: ["Evaluation", "Model Architecture"]
short_authors: Shen et al.
---
Existing benchmarks fail to capture a crucial aspect of intelligence: physical reasoning, the integrated ability to combine domain knowledge, symbolic reasoning, and understanding of real-world constraints. To address this gap, we introduce PhyX: the first large-scale benchmark designed to assess models capacity for physics-grounded reasoning in visual scenarios. PhyX includes 3K meticulously curated multimodal questions spanning 6 reasoning types across 25 sub-domains and 6 core physics domains: thermodynamics, electromagnetism, mechanics, modern physics, optics, and wave\&acoustics. In our comprehensive evaluation, even state-of-the-art models struggle significantly with physical reasoning. GPT-4o, Claude3.7-Sonnet, and GPT-o4-mini achieve only 32.5%, 42.2%, and 45.8% accuracy respectively-performance gaps exceeding 29% compared to human experts. Our analysis exposes critical limitations in current models: over-reliance on memorized disciplinary knowledge, excessive dependence on mathematical formulations, and surface-level visual pattern matching rather than genuine physical understanding. We provide in-depth analysis through fine-grained statistics, detailed case studies, and multiple evaluation paradigms to thoroughly examine physical reasoning capabilities. To ensure reproducibility, we implement a compatible evaluation protocol based on widely-used toolkits such as VLMEvalKit, enabling one-click evaluation.

https://huggingface.co/discussions/paper/68304052ffb59afb6569282f