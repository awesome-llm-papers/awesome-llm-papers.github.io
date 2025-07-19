---
layout: publication
title: Adaptive Augmentation Policy Optimization With LLM Feedback
authors: Duru Ant, Temizel Alptekin
conference: 'IEEE Transactions on Systems, Man, and Cybernetics: Systems'
year: 2024
bibkey: duru2024adaptive
citations: 90
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.13453'}]
tags: [RAG, Training Techniques, Alt, Evaluation, Model Architecture, Efficiency And
    Optimization, Reinforcement Learning, Security, Datasets]
---
Data augmentation is a critical component of deep learning pipelines,
enhancing model generalization by increasing dataset diversity. Traditional
augmentation strategies rely on manually designed transformations, stochastic
sampling, or automated search-based approaches. Although automated methods
improve performance, they often require extensive computational resources and
are tailored to specific datasets. In this work, we propose a Large Language
Model (LLM)-guided augmentation optimization strategy that refines augmentation
policies based on model performance feedback. We introduce two approaches: (1)
LLM-Guided Augmentation Policy Optimization, where augmentation policies are
selected by an LLM prior to training and iteratively refined across multiple
training cycles, and (2) Adaptive LLM-Guided Augmentation Policy Optimization,
where policies adapt in real-time based on performance metrics. This
in-training approach eliminates the need for full model retraining before
receiving LLM feedback, thereby reducing computational costs while improving
performance. Our methodology employs an LLM to dynamically select augmentation
transformations based on dataset characteristics, model architecture, and prior
training outcomes. Unlike traditional search-based methods, our approach
leverages the contextual knowledge of LLMs, particularly in specialized domains
like medical imaging, to recommend augmentation strategies tailored to
domain-specific data. We evaluate our approach on multiple domain-specific
image classification datasets where augmentation is key to model robustness.
Results show that LLM-guided augmentation optimization outperforms traditional
methods, improving model accuracy. These findings highlight the potential of
LLMs in automating and adapting deep learning training workflows.