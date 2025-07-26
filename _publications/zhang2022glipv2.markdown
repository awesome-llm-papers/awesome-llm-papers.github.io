---
layout: publication
title: 'Glipv2: Unifying Localization And Vision-language Understanding'
authors: Haotian Zhang, Pengchuan Zhang, Xiaowei Hu, Yen-chun Chen, Liunian Harold
  Li, Xiyang Dai, Lijuan Wang, Lu Yuan, Jenq-neng Hwang, Jianfeng Gao
conference: Arxiv
year: 2022
bibkey: zhang2022glipv2
citations: 85
additional_links: [{name: Code, url: 'https://github.com/microsoft/GLIP'}, {name: Paper,
    url: 'https://arxiv.org/abs/2206.05836'}]
tags: ["Few-Shot", "Has Code", "Training Techniques"]
short_authors: Zhang et al.
---
We present GLIPv2, a grounded VL understanding model, that serves both
localization tasks (e.g., object detection, instance segmentation) and
Vision-Language (VL) understanding tasks (e.g., VQA, image captioning). GLIPv2
elegantly unifies localization pre-training and Vision-Language Pre-training
(VLP) with three pre-training tasks: phrase grounding as a VL reformulation of
the detection task, region-word contrastive learning as a novel region-word
level contrastive learning task, and the masked language modeling. This
unification not only simplifies the previous multi-stage VLP procedure but also
achieves mutual benefits between localization and understanding tasks.
Experimental results show that a single GLIPv2 model (all model weights are
shared) achieves near SoTA performance on various localization and
understanding tasks. The model also shows (1) strong zero-shot and few-shot
adaption performance on open-vocabulary object detection tasks and (2) superior
grounding capability on VL understanding tasks. Code will be released at
https://github.com/microsoft/GLIP.