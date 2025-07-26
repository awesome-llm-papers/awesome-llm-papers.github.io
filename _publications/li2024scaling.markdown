---
layout: publication
title: 'Scaling (down) CLIP: A Comprehensive Analysis Of Data, Architecture, And Training
  Strategies'
authors: Zichao Li, Cihang Xie, Ekin Dogus Cubuk
conference: No Venue
year: 2024
bibkey: li2024scaling
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2404.08197'}]
tags: ["Datasets", "Model Architecture", "Training Techniques"]
short_authors: Zichao Li, Cihang Xie, Ekin Dogus Cubuk
---
This paper investigates the performance of the Contrastive Language-Image Pre-training (CLIP) when scaled down to limited computation budgets. We explore CLIP along three dimensions: data, architecture, and training strategies. With regards to data, we demonstrate the significance of high-quality training data and show that a smaller dataset of high-quality data can outperform a larger dataset with lower quality. We also examine how model performance varies with different dataset sizes, suggesting that smaller ViT models are better suited for smaller datasets, while larger models perform better on larger datasets with fixed compute. Additionally, we provide guidance on when to choose a CNN-based architecture or a ViT-based architecture for CLIP training. We compare four CLIP training strategies - SLIP, FLIP, CLIP, and CLIP+Data Augmentation - and show that the choice of training strategy depends on the available compute resource. Our analysis reveals that CLIP+Data Augmentation can achieve comparable performance to CLIP using only half of the training data. This work provides practical insights into how to effectively train and deploy CLIP models, making them more accessible and affordable for practical use in various applications.

https://huggingface.co/discussions/paper/661c8b3622ca1dfd3fe43db7