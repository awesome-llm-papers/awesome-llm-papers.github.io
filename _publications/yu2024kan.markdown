---
layout: publication
title: 'KAN Or MLP: A Fairer Comparison'
authors: Runpeng Yu, Weihao Yu, Xinchao Wang
conference: No Venue
year: 2024
bibkey: yu2024kan
additional_links: [{name: Code, url: 'https://github.com/yu-rp/KANbeFair'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/66a06d8c8a65778f7264bec4'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2407.16674'}]
tags: ["Has Code"]
short_authors: Runpeng Yu, Weihao Yu, Xinchao Wang
---
This paper does not introduce a novel method. Instead, it offers a fairer and more comprehensive comparison of KAN and MLP models across various tasks, including machine learning, computer vision, audio processing, natural language processing, and symbolic formula representation. Specifically, we control the number of parameters and FLOPs to compare the performance of KAN and MLP. Our main observation is that, except for symbolic formula representation tasks, MLP generally outperforms KAN. We also conduct ablation studies on KAN and find that its advantage in symbolic formula representation mainly stems from its B-spline activation function. When B-spline is applied to MLP, performance in symbolic formula representation significantly improves, surpassing or matching that of KAN. However, in other tasks where MLP already excels over KAN, B-spline does not substantially enhance MLP's performance. Furthermore, we find that KAN's forgetting issue is more severe than that of MLP in a standard class-incremental continual learning setting, which differs from the findings reported in the KAN paper. We hope these results provide insights for future research on KAN and other MLP alternatives. Project link: https://github.com/yu-rp/KANbeFair

https://huggingface.co/discussions/paper/66a06d8c8a65778f7264bec4