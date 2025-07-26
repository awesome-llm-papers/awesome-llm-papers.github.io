---
layout: publication
title: 'Univl: A Unified Video And Language Pre-training Model For Multimodal Understanding
  And Generation'
authors: Huaishao Luo, Lei Ji, Botian Shi, Haoyang Huang, Nan Duan, Tianrui Li, Jason
  Li, Taroon Bharti, Ming Zhou
conference: Arxiv
year: 2020
bibkey: luo2020univl
citations: 164
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2002.06353'}]
tags: ["Datasets", "Model Architecture", "Training Techniques"]
short_authors: Luo et al.
---
With the recent success of the pre-training technique for NLP and
image-linguistic tasks, some video-linguistic pre-training works are gradually
developed to improve video-text related downstream tasks. However, most of the
existing multimodal models are pre-trained for understanding tasks, leading to
a pretrain-finetune discrepancy for generation tasks. This paper proposes
UniVL: a Unified Video and Language pre-training model for both multimodal
understanding and generation. It comprises four components, including two
single-modal encoders, a cross encoder, and a decoder with the Transformer
backbone. Five objectives, including video-text joint, conditioned masked
language model (CMLM), conditioned masked frame model (CMFM), video-text
alignment, and language reconstruction, are designed to train each of the
components. We further develop two pre-training strategies, stage by stage
pre-training (StagedP) and enhanced video representation (EnhancedV), to make
the training process of the UniVL more effective. The pre-train is carried out
on a sizeable instructional video dataset HowTo100M. Experimental results
demonstrate that the UniVL can learn strong video-text representation and
achieves state-of-the-art results on five downstream tasks.