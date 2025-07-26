---
layout: publication
title: Layerwise Recurrent Router For Mixture-of-experts
authors: Zihan Qiu, Zeyu Huang, Shuang Cheng, Yizhi Zhou, Zili Wang, Ivan Titov, Jie
  Fu
conference: No Venue
year: 2024
bibkey: qiu2024layerwise
additional_links: [{name: Code, url: 'https://github.com/qiuzh20/RMoE'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/66bc2939181edd124e610ecd'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2408.06793'}]
tags: ["Has Code", "Model Architecture", "Training Techniques"]
short_authors: Qiu et al.
---
The scaling of large language models (LLMs) has revolutionized their capabilities in various tasks, yet this growth must be matched with efficient computational strategies. The Mixture-of-Experts (MoE) architecture stands out for its ability to scale model size without significantly increasing training costs. Despite their advantages, current MoE models often display parameter inefficiency. For instance, a pre-trained MoE-based LLM with 52 billion parameters might perform comparably to a standard model with 6.7 billion parameters. Being a crucial part of MoE, current routers in different layers independently assign tokens without leveraging historical routing information, potentially leading to suboptimal token-expert combinations and the parameter inefficiency problem. To alleviate this issue, we introduce the Layerwise Recurrent Router for Mixture-of-Experts (RMoE). RMoE leverages a Gated Recurrent Unit (GRU) to establish dependencies between routing decisions across consecutive layers. Such layerwise recurrence can be efficiently parallelly computed for input tokens and introduces negotiable costs. Our extensive empirical evaluations demonstrate that RMoE-based language models consistently outperform a spectrum of baseline models. Furthermore, RMoE integrates a novel computation stage orthogonal to existing methods, allowing seamless compatibility with other MoE architectures. Our analyses attribute RMoE's gains to its effective cross-layer information sharing, which also improves expert selection and diversity. Our code is at https://github.com/qiuzh20/RMoE

https://huggingface.co/discussions/paper/66bc2939181edd124e610ecd