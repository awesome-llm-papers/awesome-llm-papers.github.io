---
layout: publication
title: 'Jetmoe: Reaching Llama2 Performance With 0.1M Dollars'
authors: Yikang Shen, Zhen Guo, Tianle Cai, Zengyi Qin
conference: No Venue
year: 2024
bibkey: shen2024jetmoe
additional_links: [{name: Code, url: 'https://github.com/myshell-ai/JetMoE'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/66188b1212e9f8ef47c1baec'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2404.07413'}]
tags: ["Has Code", "Model Architecture"]
short_authors: Shen et al.
---
Large Language Models (LLMs) have achieved remarkable results, but their increasing resource demand has become a major obstacle to the development of powerful and accessible super-human intelligence. This report introduces JetMoE-8B, a new LLM trained with less than $0.1 million, using 1.25T tokens from carefully mixed open-source corpora and 30,000 H100 GPU hours. Despite its low cost, the JetMoE-8B demonstrates impressive performance, with JetMoE-8B outperforming the Llama2-7B model and JetMoE-8B-Chat surpassing the Llama2-13B-Chat model. These results suggest that LLM training can be much more cost-effective than generally thought. JetMoE-8B is based on an efficient Sparsely-gated Mixture-of-Experts (SMoE) architecture, composed of attention and feedforward experts. Both layers are sparsely activated, allowing JetMoE-8B to have 8B parameters while only activating 2B for each input token, reducing inference computation by about 70% compared to Llama2-7B. Moreover, JetMoE-8B is highly open and academia-friendly, using only public datasets and training code. All training parameters and data mixtures have been detailed in this report to facilitate future efforts in the development of open foundation models. This transparency aims to encourage collaboration and further advancements in the field of accessible and efficient LLMs. The model weights are publicly available at https://github.com/myshell-ai/JetMoE.

https://huggingface.co/discussions/paper/66188b1212e9f8ef47c1baec