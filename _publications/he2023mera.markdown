---
layout: publication
title: 'Mera: Merging Pretrained Adapters For Few-shot Learning'
authors: He et al.
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2023
bibkey: he2023mera
citations: 62
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2308.15982'}]
tags: [Training Techniques, CVPR, Few Shot, Fine Tuning, Merging]
---
Adapter tuning, which updates only a few parameters, has become a mainstream
method for fine-tuning pretrained language models to downstream tasks. However,
it often yields subpar results in few-shot learning. AdapterFusion, which
assembles pretrained adapters using composition layers tailored to specific
tasks, is a possible solution but significantly increases trainable parameters
and deployment costs. Despite this, our preliminary study reveals that even
single adapters can outperform Adapterfusion in few-shot learning, urging us to
propose \textbf\{\texttt\{Merging Pretrained Adapters\}\} (MerA) that efficiently
incorporates pretrained adapters to a single model through model fusion.
Extensive experiments on two PLMs demonstrate that MerA achieves substantial
improvements compared to both single adapters and AdapterFusion. To further
enhance the capacity of MerA, we also introduce a simple yet effective
technique, referred to as the "\textit\{same-track\}" setting, that merges
adapters from the same track of pretraining tasks. With the implementation of
the "\textit\{same-track\}" setting, we observe even more impressive gains,
surpassing the performance of both full fine-tuning and adapter tuning by a
substantial margin, e.g., 3.5% in MRPC and 5.0% in MNLI.