---
layout: publication
title: 'Fusechat: Knowledge Fusion Of Chat Models'
authors: Fanqi Wan, Ziyi Yang, Longguang Zhong, Xiaojun Quan, Xinting Huang, Wei Bi
conference: No Venue
year: 2024
bibkey: wan2024fusechat
additional_links: [{name: Code, url: 'https://github.com/fanqiwan/FuseLLM'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/65dd6bc5e731928ad80886a0'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2402.16107'}]
tags: ["Has Code", "Model Architecture", "Tools"]
short_authors: Wan et al.
---
While training large language models (LLMs) from scratch can indeed lead to models with distinct capabilities and strengths, this approach incurs substantial costs and may lead to potential redundancy in competencies. An alternative strategy is to combine existing LLMs into a more robust LLM, thereby diminishing the necessity for expensive pre-training. However, due to the diverse architectures of LLMs, direct parameter blending proves to be unfeasible. Recently, FuseLLM introduced the concept of knowledge fusion to transfer the collective knowledge of multiple structurally varied LLMs into a target LLM through lightweight continual training. In this report, we extend the scalability and flexibility of the FuseLLM framework to realize the fusion of chat LLMs, resulting in FuseChat. FuseChat comprises two main stages. Firstly, we undertake knowledge fusion for structurally and scale-varied source LLMs to derive multiple target LLMs of identical structure and size via lightweight fine-tuning. Then, these target LLMs are merged within the parameter space, wherein we propose a novel method for determining the merging weights based on the variation ratio of parameter matrices before and after fine-tuning. We validate our approach using three prominent chat LLMs with diverse architectures and scales, namely NH2-Mixtral-8x7B, NH2-Solar-10.7B, and OpenChat-3.5-7B. Experimental results spanning various chat domains demonstrate the superiority of \textsc\{FuseChat-7B\} across a broad spectrum of chat LLMs at 7B and 34B scales, even surpassing GPT-3.5 (March) and approaching Mixtral-8x7B-Instruct. Our code, model weights, and data are openly accessible at https://github.com/fanqiwan/FuseLLM.

https://huggingface.co/discussions/paper/65dd6bc5e731928ad80886a0