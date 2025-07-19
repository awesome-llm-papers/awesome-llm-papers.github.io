---
layout: publication
title: A Domain-agnostic Scalable AI Safety Ensuring Framework
authors: Kim et al.
conference: npj Digital Medicine
year: 2025
bibkey: kim2025domain
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2504.20924'}]
tags: [Training Techniques, Agentic, Tools, Efficiency And Optimization, Reinforcement
    Learning, Applications, Responsible AI]
---
Ensuring the safety of AI systems has emerged as a critical priority as these systems are increasingly deployed in real-world applications. We propose a novel domain-agnostic framework that guarantees AI systems satisfy user-defined safety constraints with specified probabilities. Our approach combines any AI model with an optimization problem that ensures outputs meet safety requirements while maintaining performance. The key challenge is handling uncertain constraints -- those whose satisfaction cannot be deterministically evaluated~(e.g., whether a chatbot response is ``harmful''). We address this through three innovations: (1) a safety classification model that assesses constraint satisfaction probability, (2) internal test data to evaluate this classifier's reliability, and (3) conservative testing to prevent overfitting when this data is used in training. We prove our method guarantees probabilistic safety under mild conditions and establish the first scaling law in AI safety -- showing that the safety-performance trade-off improves predictably with more internal test data. Experiments across production planning, reinforcement learning, and language generation demonstrate our framework achieves up to 140 times better safety than existing methods at the same performance levels. This work enables AI systems to achieve both rigorous safety guarantees and high performance across diverse domains.