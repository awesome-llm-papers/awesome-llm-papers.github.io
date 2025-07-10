---
layout: publication
title: 'R2gengpt: Radiology Report Generation With Frozen Llms'
authors: Zhanyu Wang, Lingqiao Liu, Lei Wang, Luping Zhou
conference: Meta-Radiology
year: 2023
citations: 46
bibkey: wang2023radiology
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2309.09812'}, {name: Code,
    url: 'https://github.com/wang-zhanyu/R2GenGPT'}]
tags: [Has Code, Model Architecture, GPT, Tools, Efficiency and Optimization, Training
    Techniques]
---
Large Language Models (LLMs) have consistently showcased remarkable
generalization capabilities when applied to various language tasks.
Nonetheless, harnessing the full potential of LLMs for Radiology Report
Generation (R2Gen) still presents a challenge, stemming from the inherent
disparity in modality between LLMs and the R2Gen task. To bridge this gap
effectively, we propose R2GenGPT, which is a novel solution that aligns visual
features with the word embedding space of LLMs using an efficient visual
alignment module. This innovative approach empowers the previously static LLM
to seamlessly integrate and process image information, marking a step forward
in optimizing R2Gen performance. R2GenGPT offers the following benefits. First,
it attains state-of-the-art (SOTA) performance by training only the lightweight
visual alignment module while freezing all the parameters of LLM. Second, it
exhibits high training efficiency, as it requires the training of an
exceptionally minimal number of parameters while achieving rapid convergence.
By employing delta tuning, our model only trains 5M parameters (which
constitute just 0.07% of the total parameter count) to achieve performance
close to the SOTA levels. Our code is available at
https://github.com/wang-zhanyu/R2GenGPT.