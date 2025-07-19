---
layout: publication
title: 'Boa: Attention-aware Post-training Quantization Without Backpropagation'
authors: Kim et al.
conference: Machine Learning
year: 2024
bibkey: kim2024boa
citations: 81
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2406.13474'}]
tags: [Training Techniques, Attention Mechanism, Model Architecture, ICML, Efficiency
    And Optimization, Reinforcement Learning, Quantization]
---
Post-training quantization (PTQ) is a promising solution for deploying large language models (LLMs) on resource-constrained devices. Early methods developed for small-scale networks, such as ResNet, rely on gradient-based optimization, which becomes impractical for hyper-scale LLMs with billions of parameters. While recently proposed backpropagation-free or transformation-based methods alleviate this issue, they ignore inter-layer interactions or use the naive nearest-rounding-based quantized weight assignment to save the heavy computational cost of weight optimization. In this paper, we introduce a novel backpropagation-free PTQ algorithm that optimizes quantized weights by considering inter-layer dependencies. The key innovation is the development of attention-aware Hessian matrices that capture inter-layer interactions within the attention module. Extensive experiments demonstrate that our approach not only outperforms existing weight quantization methods but also shows good synergy with conventional methods to suppress activation outliers, leading to state-of-the-art weight-activation quantization performance. The code will be available at https://github.com/SamsungLabs/BoA.