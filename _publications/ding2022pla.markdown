---
layout: publication
title: 'PLA: Language-driven Open-vocabulary 3D Scene Understanding'
authors: Ding et al.
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2022
bibkey: ding2022pla
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2211.16312'}]
tags: [Multimodal Models, RAG, CVPR]
---
Open-vocabulary scene understanding aims to localize and recognize unseen
categories beyond the annotated label space. The recent breakthrough of 2D
open-vocabulary perception is largely driven by Internet-scale paired
image-text data with rich vocabulary concepts. However, this success cannot be
directly transferred to 3D scenarios due to the inaccessibility of large-scale
3D-text pairs. To this end, we propose to distill knowledge encoded in
pre-trained vision-language (VL) foundation models through captioning
multi-view images from 3D, which allows explicitly associating 3D and
semantic-rich captions. Further, to foster coarse-to-fine visual-semantic
representation learning from captions, we design hierarchical 3D-caption pairs,
leveraging geometric constraints between 3D scenes and multi-view images.
Finally, by employing contrastive learning, the model learns language-aware
embeddings that connect 3D and text for open-vocabulary tasks. Our method not
only remarkably outperforms baseline methods by 25.8% \\(\sim\\) 44.7% hIoU and
14.5% \\(\sim\\) 50.4% hAP\\(_\{50\}\\) in open-vocabulary semantic and instance
segmentation, but also shows robust transferability on challenging zero-shot
domain transfer tasks. See the project website at
https://dingry.github.io/projects/PLA.