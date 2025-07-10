---
layout: publication
title: 'Altclip: Altering The Language Encoder In CLIP For Extended Language Capabilities'
authors: Zhongzhi Chen et al.
conference: 'Findings of the Association for Computational Linguistics: ACL 2023'
year: 2022
citations: 17
bibkey: chen2022altering
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2211.06679'}, {name: Code,
    url: 'https://github.com/FlagAI-Open/FlagAI'}]
tags: [Has Code, Training Techniques, Multimodal Models, Evaluation]
---
In this work, we present a conceptually simple and effective method to train
a strong bilingual/multilingual multimodal representation model. Starting from
the pre-trained multimodal representation model CLIP released by OpenAI, we
altered its text encoder with a pre-trained multilingual text encoder XLM-R,
and aligned both languages and image representations by a two-stage training
schema consisting of teacher learning and contrastive learning. We validate our
method through evaluations of a wide range of tasks. We set new
state-of-the-art performances on a bunch of tasks including ImageNet-CN,
Flicker30k-CN, COCO-CN and XTD. Further, we obtain very close performances with
CLIP on almost all tasks, suggesting that one can simply alter the text encoder
in CLIP for extended capabilities such as multilingual understanding. Our
models and code are available at https://github.com/FlagAI-Open/FlagAI.