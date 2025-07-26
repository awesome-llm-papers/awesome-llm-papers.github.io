---
layout: publication
title: 'Megalodon: Efficient LLM Pretraining And Inference With Unlimited Context
  Length'
authors: Xuezhe Ma, Xiaomeng Yang, Wenhan Xiong, Beidi Chen, Lili Yu, Hao Zhang, Jonathan
  May, Luke Zettlemoyer, Omer Levy, Chunting Zhou
conference: No Venue
year: 2024
bibkey: ma2024megalodon
additional_links: [{name: Code, url: 'https://github.com/XuezheMax/megalodon'}, {
    name: Code, url: 'https://huggingface.co/discussions/paper/661df6c69945e0962d7545da'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2404.08801'}]
tags: ["Efficiency", "Memory & Context", "Model Architecture", "Training Techniques"]
short_authors: Ma et al.
---
The quadratic complexity and weak length extrapolation of Transformers limits their ability to scale to long sequences, and while sub-quadratic solutions like linear attention and state space models exist, they empirically underperform Transformers in pretraining efficiency and downstream task accuracy. We introduce Megalodon, a neural architecture for efficient sequence modeling with unlimited context length. Megalodon inherits the architecture of Mega (exponential moving average with gated attention), and further introduces multiple technical components to improve its capability and stability, including complex exponential moving average (CEMA), timestep normalization layer, normalized attention mechanism and pre-norm with two-hop residual configuration. In a controlled head-to-head comparison with Llama2, Megalodon achieves better efficiency than Transformer in the scale of 7 billion parameters and 2 trillion training tokens. Megalodon reaches a training loss of 1.70, landing mid-way between Llama2-7B (1.75) and 13B (1.67). Code: https://github.com/XuezheMax/megalodon

https://huggingface.co/discussions/paper/661df6c69945e0962d7545da