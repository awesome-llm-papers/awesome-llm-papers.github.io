---
layout: publication
title: Iterative Deepening Sampling As Efficient Test-time Scaling
authors: Chen Weizhe, Koenig Sven, Dilkina Bistra
conference: Artificial Intelligence
year: 2025
bibkey: chen2025iterative
citations: 59
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.05449'}]
tags: [Scaling Laws, Training Techniques, Tools, IJCAI, Evaluation, Efficiency And
    Optimization, AISTATS, UAI, Large Scale Training, AAAI, Datasets]
---
Recent reasoning models, such as OpenAI's O1 series, have demonstrated exceptional performance on complex reasoning tasks and revealed new test-time scaling laws. Inspired by this, many people have been studying how to train models to achieve effective self-evaluation and self-correction to further enable the scaling paradigm. However, less studied is how to efficiently scale test-time compute from a fixed model, and this remains a challenge. In this paper, we address this challenge by focusing on enhancing the quality of self-reflection data generation for complex problem-solving at test time, which can also subsequently improve the training of next-generation large language models (LLMs). Specifically, we explore how systematically triggering a model's self-correction mechanisms can improve performance on challenging reasoning tasks. To this end, we propose a novel iterative deepening sampling algorithm framework designed to enhance self-correction and generate higher-quality samples. Through extensive experiments on Math500 and AIME benchmarks, we demonstrate that our method achieves a higher success rate on difficult tasks and provide detailed ablation studies to analyze its effectiveness across diverse settings.