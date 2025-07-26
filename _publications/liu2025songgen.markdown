---
layout: publication
title: 'Songgen: A Single Stage Auto-regressive Transformer For Text-to-song Generation'
authors: Zihan Liu, Shuangrui Ding, Zhixiong Zhang, Xiaoyi Dong, Pan Zhang, Yuhang
  Zang, Yuhang Cao, Dahua Lin, Jiaqi Wang
conference: No Venue
year: 2025
bibkey: liu2025songgen
additional_links: [{name: Code, url: 'https://liuzh-19.github.io/SongGen/'}, {name: Code,
    url: 'https://github.com/LiuZH-19/SongGen'}, {name: Code, url: 'https://huggingface.co/discussions/paper/67b6c698e9b901edeaf321a7'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2502.13128'}]
tags: ["Applications", "Model Architecture"]
short_authors: Liu et al.
---
Text-to-song generation, the task of creating vocals and accompaniment from textual inputs, poses significant challenges due to domain complexity and data scarcity. Existing approaches often employ multi-stage generation procedures, resulting in cumbersome training and inference pipelines. In this paper, we propose SongGen, a fully open-source, single-stage auto-regressive transformer designed for controllable song generation. The proposed model facilitates fine-grained control over diverse musical attributes, including lyrics and textual descriptions of instrumentation, genre, mood, and timbre, while also offering an optional three-second reference clip for voice cloning. Within a unified auto-regressive framework, SongGen supports two output modes: mixed mode, which generates a mixture of vocals and accompaniment directly, and dual-track mode, which synthesizes them separately for greater flexibility in downstream applications. We explore diverse token pattern strategies for each mode, leading to notable improvements and valuable insights. Furthermore, we design an automated data preprocessing pipeline with effective quality control. To foster community engagement and future research, we will release our model weights, training code, annotated data, and preprocessing pipeline. The generated samples are showcased on our project page at https://liuzh-19.github.io/SongGen/ , and the code will be available at https://github.com/LiuZH-19/SongGen .

https://huggingface.co/discussions/paper/67b6c698e9b901edeaf321a7