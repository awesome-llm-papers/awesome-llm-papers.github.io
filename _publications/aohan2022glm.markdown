---
layout: publication
title: 'GLM-130B: An Open Bilingual Pre-trained Model'
authors: [aohan Zeng, xiao Liu, zhengxiao Du, zihan Wang, hanyu Lai, ming Ding, zhuoyi
    Yang, yifan Xu, wendi Zheng, xiao Xia, weng Lam Tam, zixuan Ma, yufei Xue, jidong
    Zhai, wenguang Chen, peng Zhang, yuxiao Dong, jie Tang]
conference: Arxiv
year: 2022
bibkey: aohan2022glm
citations: 251
additional_links: [{name: Code, url: 'https://github.com/THUDM/GLM-130B/'}, {name: Paper,
    url: 'http://arxiv.org/abs/2210.02414v2'}]
tags: ["Has Code", "Model Architecture"]
short_authors: Zeng et al.
---
We introduce GLM-130B, a bilingual (English and Chinese) pre-trained language
model with 130 billion parameters. It is an attempt to open-source a 100B-scale
model at least as good as GPT-3 (davinci) and unveil how models of such a scale
can be successfully pre-trained. Over the course of this effort, we face
numerous unexpected technical and engineering challenges, particularly on loss
spikes and divergence. In this paper, we introduce the training process of
GLM-130B including its design choices, training strategies for both efficiency
and stability, and engineering efforts. The resultant GLM-130B model offers
significant outperformance over GPT-3 175B (davinci) on a wide range of popular
English benchmarks while the performance advantage is not observed in OPT-175B
and BLOOM-176B. It also consistently and significantly outperforms ERNIE TITAN
3.0 260B -- the largest Chinese language model -- across related benchmarks.
Finally, we leverage a unique scaling property of GLM-130B to reach INT4
quantization without post training, with almost no performance loss, making it
the first among 100B-scale models and more importantly, allowing its effective
inference on 4\\(\times\\)RTX 3090 (24G) or 8\\(\times\\)RTX 2080 Ti (11G) GPUs, the
most affordable GPUs required for using 100B-scale models. The GLM-130B model
weights are publicly accessible and its code, training logs, related toolkit,
and lessons learned are open-sourced at
https://github.com/THUDM/GLM-130B/.