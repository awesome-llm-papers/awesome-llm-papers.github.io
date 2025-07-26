---
layout: publication
title: Should We Still Pretrain Encoders With Masked Language Modeling?
authors: "Hippolyte Gisserot-boukhlef, Nicolas Boizard, Manuel Faysse, Duarte M. Alves,\
  \ Emmanuel Malherbe, Andr\xE9 F. T. Martins, C\xE9line Hudelot, Pierre Colombo"
conference: No Venue
year: 2025
bibkey: gisserotboukhlef2025should
additional_links: [{name: Code, url: 'https://hf.co/MLMvsCLM'}, {name: Code, url: 'https://huggingface.co/discussions/paper/6864e267d59a9eda59024bb3'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2507.00994'}]
tags: ["Fine-Tuning", "Training Techniques"]
short_authors: Gisserot-boukhlef et al.
---
Learning high-quality text representations is fundamental to a wide range of NLP tasks. While encoder pretraining has traditionally relied on Masked Language Modeling (MLM), recent evidence suggests that decoder models pretrained with Causal Language Modeling (CLM) can be effectively repurposed as encoders, often surpassing traditional encoders on text representation benchmarks. However, it remains unclear whether these gains reflect an inherent advantage of the CLM objective or arise from confounding factors such as model and data scale. In this paper, we address this question through a series of large-scale, carefully controlled pretraining ablations, training a total of 30 models ranging from 210 million to 1 billion parameters, and conducting over 15,000 fine-tuning and evaluation runs. We find that while training with MLM generally yields better performance across text representation tasks, CLM-trained models are more data-efficient and demonstrate improved fine-tuning stability. Building on these findings, we experimentally show that a biphasic training strategy that sequentially applies CLM and then MLM, achieves optimal performance under a fixed computational training budget. Moreover, we demonstrate that this strategy becomes more appealing when initializing from readily available pretrained CLM models (from the existing LLM ecosystem), reducing the computational burden needed to train best-in-class encoder models. We release all project artifacts at https://hf.co/MLMvsCLM to foster further research.

https://huggingface.co/discussions/paper/6864e267d59a9eda59024bb3