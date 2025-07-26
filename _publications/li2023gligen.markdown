---
layout: publication
title: 'GLIGEN: Open-set Grounded Text-to-image Generation'
authors: Yuheng Li, Haotian Liu, Qingyang Wu, Fangzhou Mu, Jianwei Yang, Jianfeng
  Gao, Chunyuan Li, Yong Jae Lee
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2023
bibkey: li2023gligen
citations: 249
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2301.07093'}]
tags: ["CVPR"]
short_authors: Li et al.
---
Large-scale text-to-image diffusion models have made amazing advances.
However, the status quo is to use text input alone, which can impede
controllability. In this work, we propose GLIGEN, Grounded-Language-to-Image
Generation, a novel approach that builds upon and extends the functionality of
existing pre-trained text-to-image diffusion models by enabling them to also be
conditioned on grounding inputs. To preserve the vast concept knowledge of the
pre-trained model, we freeze all of its weights and inject the grounding
information into new trainable layers via a gated mechanism. Our model achieves
open-world grounded text2img generation with caption and bounding box condition
inputs, and the grounding ability generalizes well to novel spatial
configurations and concepts. GLIGEN's zero-shot performance on COCO and LVIS
outperforms that of existing supervised layout-to-image baselines by a large
margin.