---
layout: publication
title: Parallel Scaling Law For Language Models
authors: Mouxiang Chen, Binyuan Hui, Zeyu Cui, Jiaxi Yang, Dayiheng Liu, Jianling
  Sun, Junyang Lin, Zhongxin Liu
conference: No Venue
year: 2025
bibkey: chen2025parallel
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2505.10475'}]
tags: ["Efficiency", "Training Techniques"]
short_authors: Chen et al.
---
It is commonly believed that scaling language models should commit a significant space or time cost, by increasing the parameters (parameter scaling) or output tokens (inference-time scaling). We introduce the third and more inference-efficient scaling paradigm: increasing the model's parallel computation during both training and inference time. We apply P diverse and learnable transformations to the input, execute forward passes of the model in parallel, and dynamically aggregate the P outputs. This method, namely parallel scaling (ParScale), scales parallel computation by reusing existing parameters and can be applied to any model structure, optimization procedure, data, or task. We theoretically propose a new scaling law and validate it through large-scale pre-training, which shows that a model with P parallel streams is similar to scaling the parameters by O(log P) while showing superior inference efficiency. For example, ParScale can use up to 22times less memory increase and 6times less latency increase compared to parameter scaling that achieves the same performance improvement. It can also recycle an off-the-shelf pre-trained model into a parallelly scaled one by post-training on a small amount of tokens, further reducing the training budget. The new scaling law we discovered potentially facilitates the deployment of more powerful models in low-resource scenarios, and provides an alternative perspective for the role of computation in machine learning.

https://huggingface.co/discussions/paper/68271b1f228dc6f5fd90b18d