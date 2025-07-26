---
layout: publication
title: 'Regionclip: Region-based Language-image Pretraining'
authors: Yiwu Zhong, Jianwei Yang, Pengchuan Zhang, Chunyuan Li, Noel Codella, Liunian
  Harold Li, Luowei Zhou, Xiyang Dai, Lu Yuan, Yin Li, Jianfeng Gao
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2022
bibkey: zhong2021regionclip
citations: 297
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2112.09106'}]
tags: ["CVPR"]
short_authors: Zhong et al.
---
Contrastive language-image pretraining (CLIP) using image-text pairs has
achieved impressive results on image classification in both zero-shot and
transfer learning settings. However, we show that directly applying such models
to recognize image regions for object detection leads to poor performance due
to a domain shift: CLIP was trained to match an image as a whole to a text
description, without capturing the fine-grained alignment between image regions
and text spans. To mitigate this issue, we propose a new method called
RegionCLIP that significantly extends CLIP to learn region-level visual
representations, thus enabling fine-grained alignment between image regions and
textual concepts. Our method leverages a CLIP model to match image regions with
template captions and then pretrains our model to align these region-text pairs
in the feature space. When transferring our pretrained model to the
open-vocabulary object detection tasks, our method significantly outperforms
the state of the art by 3.8 AP50 and 2.2 AP for novel categories on COCO and
LVIS datasets, respectively. Moreoever, the learned region representations
support zero-shot inference for object detection, showing promising results on
both COCO and LVIS datasets. Our code is available at
https://github.com/microsoft/RegionCLIP.