---
layout: publication
title: Conditional Prompt Learning For Vision-language Models
authors: Kaiyang Zhou, Jingkang Yang, Chen Change Loy, Ziwei Liu
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2022
bibkey: zhou2022conditional
citations: 753
additional_links: [{name: Code, url: 'https://github.com/KaiyangZhou/CoOp'}, {name: Paper,
    url: 'https://arxiv.org/abs/2203.05557'}]
tags: ["CVPR", "Prompting", "Training Techniques"]
short_authors: Zhou et al.
---
With the rise of powerful pre-trained vision-language models like CLIP, it
becomes essential to investigate ways to adapt these models to downstream
datasets. A recently proposed method named Context Optimization (CoOp)
introduces the concept of prompt learning -- a recent trend in NLP -- to the
vision domain for adapting pre-trained vision-language models. Specifically,
CoOp turns context words in a prompt into a set of learnable vectors and, with
only a few labeled images for learning, can achieve huge improvements over
intensively-tuned manual prompts. In our study we identify a critical problem
of CoOp: the learned context is not generalizable to wider unseen classes
within the same dataset, suggesting that CoOp overfits base classes observed
during training. To address the problem, we propose Conditional Context
Optimization (CoCoOp), which extends CoOp by further learning a lightweight
neural network to generate for each image an input-conditional token (vector).
Compared to CoOp's static prompts, our dynamic prompts adapt to each instance
and are thus less sensitive to class shift. Extensive experiments show that
CoCoOp generalizes much better than CoOp to unseen classes, even showing
promising transferability beyond a single dataset; and yields stronger domain
generalization performance as well. Code is available at
https://github.com/KaiyangZhou/CoOp.