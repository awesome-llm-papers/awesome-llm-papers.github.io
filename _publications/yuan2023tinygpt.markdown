---
layout: publication
title: 'Tinygpt-v: Efficient Multimodal Large Language Model Via Small Backbones'
authors: Zhengqing Yuan, Zhaoxu Li, Lichao Sun
conference: No Venue
year: 2023
bibkey: yuan2023tinygpt
additional_links: [{name: Code, url: 'https://github.com/DLYuanGod/TinyGPT-V'}, {
    name: Code, url: 'https://huggingface.co/Tyrannosaurus/TinyGPT-V'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/658e28fef7291078f975c927'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2312.16862'}]
tags: ["Efficiency", "Has Code", "Model Architecture", "Training Techniques"]
short_authors: Zhengqing Yuan, Zhaoxu Li, Lichao Sun
---
In the era of advanced multimodel learning, multimodal large language models (MLLMs) such as GPT-4V have made remarkable strides towards bridging language and visual elements. However, the closed-source nature and considerable computational demand present notable challenges for universal usage and modifications. This is where open-source MLLMs like LLaVA and MiniGPT-4 come in, presenting groundbreaking achievements across tasks. Despite these accomplishments, computational efficiency remains an unresolved issue, as these models, like LLaVA-v1.5-13B, require substantial resources. Addressing these issues, we introduce TinyGPT-V, a new-wave model marrying impressive performance with commonplace computational capacity. It stands out by requiring merely a 24G GPU for training and an 8G GPU or CPU for inference. Built upon Phi-2, TinyGPT-V couples an effective language backbone with pre-trained vision modules from BLIP-2 or CLIP. TinyGPT-V's 2.8B parameters can undergo a unique quantisation process, suitable for local deployment and inference tasks on 8G various devices. Our work fosters further developments for designing cost-effective, efficient, and high-performing MLLMs, expanding their applicability in a broad array of real-world scenarios. Furthermore this paper proposed a new paradigm of Multimodal Large Language Model via small backbones. Our code and training weights are placed at: https://github.com/DLYuanGod/TinyGPT-V and https://huggingface.co/Tyrannosaurus/TinyGPT-V respectively.

https://huggingface.co/discussions/paper/658e28fef7291078f975c927