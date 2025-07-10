---
layout: publication
title: 'EVA-02: A Visual Representation For Neon Genesis'
authors: Yuxin Fang et al.
conference: Image and Vision Computing
year: 2023
citations: 41
bibkey: fang2023eva
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.11331'}, {name: Code,
    url: 'https://github.com/baaivision/EVA/tree/master/EVA-02'}]
tags: [Has Code, Model Architecture, Transformer, Fine-Tuning, Arxiv, Pre-Training,
  Training Techniques]
---
We launch EVA-02, a next-generation Transformer-based visual representation
pre-trained to reconstruct strong and robust language-aligned vision features
via masked image modeling. With an updated plain Transformer architecture as
well as extensive pre-training from an open & accessible giant CLIP vision
encoder, EVA-02 demonstrates superior performance compared to prior
state-of-the-art approaches across various representative vision tasks, while
utilizing significantly fewer parameters and compute budgets. Notably, using
exclusively publicly accessible training data, EVA-02 with only 304M parameters
achieves a phenomenal 90.0 fine-tuning top-1 accuracy on ImageNet-1K val set.
Additionally, our EVA-02-CLIP can reach up to 80.4 zero-shot top-1 on
ImageNet-1K, outperforming the previous largest & best open-sourced CLIP with
only ~1/6 parameters and ~1/6 image-text training data. We offer four EVA-02
variants in various model sizes, ranging from 6M to 304M parameters, all with
impressive performance. To facilitate open access and open research, we release
the complete suite of EVA-02 to the community at
https://github.com/baaivision/EVA/tree/master/EVA-02.