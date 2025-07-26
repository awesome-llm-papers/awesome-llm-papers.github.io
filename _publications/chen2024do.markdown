---
layout: publication
title: Do NOT Think That Much For 2+3=? On The Overthinking Of O1-like Llms
authors: Xingyu Chen, Jiahao Xu, Tian Liang, Zhiwei He, Jianhui Pang, Dian Yu, Linfeng
  Song, Qiuzhi Liu, Mengfei Zhou, Zhuosheng Zhang, Rui Wang, Zhaopeng Tu, Haitao Mi,
  Dong Yu
conference: No Venue
year: 2024
bibkey: chen2024do
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2412.21187'}]
tags: ["Efficiency", "Evaluation", "Prompting", "Training Techniques"]
short_authors: Chen et al.
---
The remarkable performance of models like the OpenAI o1 can be attributed to their ability to emulate human-like long-time thinking during inference. These models employ extended chain-of-thought (CoT) processes, exploring multiple strategies to enhance problem-solving capabilities. However, a critical question remains: How to intelligently and efficiently scale computational resources during testing. This paper presents the first comprehensive study on the prevalent issue of overthinking in these models, where excessive computational resources are allocated for simple problems with minimal benefit. We introduce novel efficiency metrics from both outcome and process perspectives to evaluate the rational use of computational resources by o1-like models. Using a self-training paradigm, we propose strategies to mitigate overthinking, streamlining reasoning processes without compromising accuracy. Experimental results show that our approach successfully reduces computational overhead while preserving model performance across a range of testsets with varying difficulty levels, such as GSM8K, MATH500, GPQA, and AIME.

https://huggingface.co/discussions/paper/6773f75b23a7829936cb3729