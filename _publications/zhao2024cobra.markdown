---
layout: publication
title: 'Cobra: Extending Mamba To Multi-modal Large Language Model For Efficient Inference'
authors: Han Zhao, Min Zhang, Wei Zhao, Pengxiang Ding, Siteng Huang, Donglin Wang
conference: No Venue
year: 2024
bibkey: zhao2024cobra
additional_links: [{name: Code, url: 'https://sites.google.com/view/cobravlm'}, {
    name: Code, url: 'https://huggingface.co/discussions/paper/65fd0a414d36be78e694bd2a'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2403.14520'}]
tags: ["Efficiency", "Model Architecture"]
short_authors: Zhao et al.
---
In recent years, the application of multimodal large language models (MLLM) in various fields has achieved remarkable success. However, as the foundation model for many downstream tasks, current MLLMs are composed of the well-known Transformer network, which has a less efficient quadratic computation complexity. To improve the efficiency of such basic models, we propose Cobra, a linear computational complexity MLLM. Specifically, Cobra integrates the efficient Mamba language model into the visual modality. Moreover, we explore and study various modal fusion schemes to create an effective multi-modal Mamba. Extensive experiments demonstrate that (1) Cobra achieves extremely competitive performance with current computationally efficient state-of-the-art methods, e.g., LLaVA-Phi, TinyLLaVA, and MobileVLM v2, and has faster speed due to Cobra's linear sequential modeling. (2) Interestingly, the results of closed-set challenging prediction benchmarks show that Cobra performs well in overcoming visual illusions and spatial relationship judgments. (3) Notably, Cobra even achieves comparable performance to LLaVA with about 43% of the number of parameters. We will make all codes of Cobra open-source and hope that the proposed method can facilitate future research on complexity problems in MLLM. Our project page is available at: https://sites.google.com/view/cobravlm.

https://huggingface.co/discussions/paper/65fd0a414d36be78e694bd2a