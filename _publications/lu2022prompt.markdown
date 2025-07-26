---
layout: publication
title: Prompt Distribution Learning
authors: Yuning Lu, Jianzhuang Liu, Yonggang Zhang, Yajing Liu, Xinmei Tian
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2022
bibkey: lu2022prompt
citations: 135
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2205.03340'}]
tags: ["CVPR", "Prompting"]
short_authors: Lu et al.
---
We present prompt distribution learning for effectively adapting a
pre-trained vision-language model to address downstream recognition tasks. Our
method not only learns low-bias prompts from a few samples but also captures
the distribution of diverse prompts to handle the varying visual
representations. In this way, we provide high-quality task-related content for
facilitating recognition. This prompt distribution learning is realized by an
efficient approach that learns the output embeddings of prompts instead of the
input embeddings. Thus, we can employ a Gaussian distribution to model them
effectively and derive a surrogate loss for efficient training. Extensive
experiments on 12 datasets demonstrate that our method consistently and
significantly outperforms existing methods. For example, with 1 sample per
category, it relatively improves the average result by 9.1% compared to
human-crafted prompts.