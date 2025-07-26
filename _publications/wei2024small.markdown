---
layout: publication
title: Small Language Model Meets With Reinforced Vision Vocabulary
authors: Haoran Wei, Lingyu Kong, Jinyue Chen, Liang Zhao, Zheng Ge, En Yu, Jianjian
  Sun, Chunrui Han, Xiangyu Zhang
conference: No Venue
year: 2024
bibkey: wei2024small
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/65b07b8699d765b854da1ee5'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2401.12503'}]
tags: ["Reinforcement Learning"]
short_authors: Wei et al.
---
Playing Large Vision Language Models (LVLMs) in 2023 is trendy among the AI community. However, the relatively large number of parameters (more than 7B) of popular LVLMs makes it difficult to train and deploy on consumer GPUs, discouraging many researchers with limited resources. Imagine how cool it would be to experience all the features of current LVLMs on an old GTX1080ti (our only game card). Accordingly, we present Vary-toy in this report, a small-size Vary along with Qwen-1.8B as the base ``large'' language model. In Vary-toy, we introduce an improved vision vocabulary, allowing the model to not only possess all features of Vary but also gather more generality. Specifically, we replace negative samples of natural images with positive sample data driven by object detection in the procedure of generating vision vocabulary, more sufficiently utilizing the capacity of the vocabulary network and enabling it to efficiently encode visual information corresponding to natural objects. For experiments, Vary-toy can achieve 65.6% ANLS on DocVQA, 59.1% accuracy on ChartQA, 88.1% accuracy on RefCOCO, and 29% on MMVet. The code will be publicly available on the homepage.

https://huggingface.co/discussions/paper/65b07b8699d765b854da1ee5