---
layout: publication
title: 'Escaping The Spuriverse: Can Large Vision-language Models Generalize Beyond
  Seen Spurious Correlations?'
authors: Yang et al.
conference: Arxiv
year: 2025
bibkey: yang2025escaping
citations: 121
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.18322'}]
tags: [Training Techniques, GPT, Tools, Evaluation, Model Architecture, Reinforcement
    Learning, Fine Tuning, Multimodal Models, Datasets]
---
Finetuning can cause spurious correlations to arise between non-essential features and the target labels, but benchmarks to study these effects involve contrived settings and narrow tasks. In contrast, we consider spurious correlations in multi-modal Large Vision Language Models (LVLMs) pretrained on extensive and diverse datasets without explicit task supervision. We develop a benchmark by sourcing GPT-4o errors on real-world visual-question-answering (VQA) benchmarks, then curating a subset through LVLM-human annotation and synthetic counterfactual evaluation to identify errors caused by spurious correlations. This process yields SpuriVerse, a novel benchmark comprised of 124 distinct types of spurious correlations extracted from real-world datasets, each containing 1 realistic and 10 synthetic VQA samples for a total of 1364 multiple choice questions. We evaluate 15 open and closed-source LVLMs on SpuriVerse, finding that even state-of-the-art closed-source models struggle significantly, achieving at best only 37.1% accuracy. Fine-tuning on synthetic examples that emphasize the spurious correlation improves performance to 78.40%, suggesting that training on diverse spurious patterns generalizes to unseen situations: models appear to learn to avoid "shortcuts" and attend to the overall image context.