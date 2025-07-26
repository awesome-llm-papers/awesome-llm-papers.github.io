---
layout: publication
title: 'RMT: Retentive Networks Meet Vision Transformers'
authors: Qihang Fan, Huaibo Huang, Mingrui Chen, Hongmin Liu, Ran He
conference: No Venue
year: 2023
bibkey: fan2023rmt
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2309.11523'}]
tags: ["Model Architecture"]
short_authors: Fan et al.
---
Transformer first appears in the field of natural language processing and is later migrated to the computer vision domain, where it demonstrates excellent performance in vision tasks. However, recently, Retentive Network (RetNet) has emerged as an architecture with the potential to replace Transformer, attracting widespread attention in the NLP community. Therefore, we raise the question of whether transferring RetNet's idea to vision can also bring outstanding performance to vision tasks. To address this, we combine RetNet and Transformer to propose RMT. Inspired by RetNet, RMT introduces explicit decay into the vision backbone, bringing prior knowledge related to spatial distances to the vision model. This distance-related spatial prior allows for explicit control of the range of tokens that each token can attend to. Additionally, to reduce the computational cost of global modeling, we decompose this modeling process along the two coordinate axes of the image. Abundant experiments have demonstrated that our RMT exhibits exceptional performance across various computer vision tasks. For example, RMT achieves 84.1% Top1-acc on ImageNet-1k using merely 4.5G FLOPs. To the best of our knowledge, among all models, RMT achieves the highest Top1-acc when models are of similar size and trained with the same strategy. Moreover, RMT significantly outperforms existing vision backbones in downstream tasks such as object detection, instance segmentation, and semantic segmentation. Our work is still in progress.

https://huggingface.co/discussions/paper/650d142844ab290c35942b6f