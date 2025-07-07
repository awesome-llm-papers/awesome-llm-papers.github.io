---
layout: publication
title: 'Minillm: Knowledge Distillation Of Large Language Models'
authors: Yuxian Gu, Li Dong, Furu Wei, Minlie Huang
conference: Arxiv
year: 2023
citations: 16
bibkey: gu2023knowledge
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2306.08543'}, {name: Code,
    url: 'https://github.com/microsoft/LMOps/tree/main/minillm'}]
tags: [Ethics and Bias, Distillation, GPT, Training Techniques, Tools, Efficiency
    and Optimization, Has Code, Language Modeling, Model Architecture]
---
Knowledge Distillation (KD) is a promising technique for reducing the high
computational demand of large language models (LLMs). However, previous KD
methods are primarily applied to white-box classification models or training
small models to imitate black-box model APIs like ChatGPT. How to effectively
distill the knowledge of white-box LLMs into small models is still
under-explored, which becomes more important with the prosperity of open-source
LLMs. In this work, we propose a KD approach that distills LLMs into smaller
language models. We first replace the forward Kullback-Leibler divergence (KLD)
objective in the standard KD approaches with reverse KLD, which is more
suitable for KD on generative language models, to prevent the student model
from overestimating the low-probability regions of the teacher distribution.
Then, we derive an effective optimization approach to learn this objective. The
student models are named MiniLLM. Extensive experiments in the
instruction-following setting show that MiniLLM generates more precise
responses with higher overall quality, lower exposure bias, better calibration,
and higher long-text generation performance than the baselines. Our method is
scalable for different model families with 120M to 13B parameters. Our code,
data, and model checkpoints can be found in
https://github.com/microsoft/LMOps/tree/main/minillm.