---
layout: publication
title: AI And Memory Wall
authors: Gholami et al.
conference: IEEE Micro
year: 2024
bibkey: gholami2024ai
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2403.14123'}]
tags: [Scaling Laws, Training Techniques, Transformer, Model Architecture, Efficiency
    And Optimization, Reinforcement Learning, Applications, Large Scale Training]
---
The availability of unprecedented unsupervised training data, along with
neural scaling laws, has resulted in an unprecedented surge in model size and
compute requirements for serving/training LLMs. However, the main performance
bottleneck is increasingly shifting to memory bandwidth. Over the past 20
years, peak server hardware FLOPS has been scaling at 3.0x/2yrs, outpacing the
growth of DRAM and interconnect bandwidth, which have only scaled at 1.6 and
1.4 times every 2 years, respectively. This disparity has made memory, rather
than compute, the primary bottleneck in AI applications, particularly in
serving. Here, we analyze encoder and decoder Transformer models and show how
memory bandwidth can become the dominant bottleneck for decoder models. We
argue for a redesign in model architecture, training, and deployment strategies
to overcome this memory limitation.