---
layout: publication
title: 'Scaling Down To Scale Up: A Guide To Parameter-efficient Fine-tuning'
authors: Vladislav Lialin, Vijeta Deshpande, Xiaowei Yao, Anna Rumshisky
conference: Arxiv
year: 2023
citations: 49
bibkey: lialin2023scaling
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.15647'}]
tags: [Efficiency and Optimization, Fine-Tuning, Reinforcement Learning, Training
    Techniques]
---
This paper presents a systematic overview of parameter-efficient fine-tuning
methods, covering over 50 papers published between early 2019 and mid-2024.
These methods aim to address the challenges of fine-tuning large language
models by training only a small subset of parameters. We provide a taxonomy
that covers a broad range of methods and present a detailed method comparison
with a specific focus on real-life efficiency in fine-tuning multibillion-scale
language models. We also conduct an extensive head-to-head experimental
comparison of 15 diverse PEFT methods, evaluating their performance and
efficiency on models up to 11B parameters. Our findings reveal that methods
previously shown to surpass a strong LoRA baseline face difficulties in
resource-constrained settings, where hyperparameter optimization is limited and
the network is fine-tuned only for a few epochs. Finally, we provide a set of
practical recommendations for using PEFT methods and outline potential future
research directions.