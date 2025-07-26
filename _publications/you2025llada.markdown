---
layout: publication
title: 'Llada-v: Large Language Diffusion Models With Visual Instruction Tuning'
authors: Zebin You, Shen Nie, Xiaolu Zhang, Jun Hu, Jun Zhou, Zhiwu Lu, Ji-rong Wen,
  Chongxuan Li
conference: No Venue
year: 2025
bibkey: you2025llada
additional_links: [{name: Code, url: 'https://ml-gsai.github.io/LLaDA-V-demo/'}, {
    name: Code, url: 'https://huggingface.co/discussions/paper/682fe37cb998c9f79463b5ae'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2505.16933'}]
tags: ["Has Code", "Model Architecture"]
short_authors: You et al.
---
In this work, we introduce LLaDA-V, a purely diffusion-based Multimodal Large Language Model (MLLM) that integrates visual instruction tuning with masked diffusion models, representing a departure from the autoregressive paradigms dominant in current multimodal approaches. Built upon LLaDA, a representative large language diffusion model, LLaDA-V incorporates a vision encoder and MLP connector that projects visual features into the language embedding space, enabling effective multimodal alignment. Our empirical investigation reveals several intriguing results: First, LLaDA-V demonstrates promising multimodal performance despite its language model being weaker on purely textual tasks than counterparts like LLaMA3-8B and Qwen2-7B. When trained on the same instruction data, LLaDA-V is highly competitive to LLaMA3-V across multimodal tasks with better data scalability. It also narrows the performance gap to Qwen2-VL, suggesting the effectiveness of its architecture for multimodal tasks. Second, LLaDA-V achieves state-of-the-art performance in multimodal understanding compared to existing hybrid autoregressive-diffusion and purely diffusion-based MLLMs. Our findings suggest that large language diffusion models show promise in multimodal contexts and warrant further investigation in future research. Project page and codes: https://ml-gsai.github.io/LLaDA-V-demo/.

https://huggingface.co/discussions/paper/682fe37cb998c9f79463b5ae