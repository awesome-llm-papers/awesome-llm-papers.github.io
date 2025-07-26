---
layout: publication
title: 'Maskclip: Masked Self-distillation Advances Contrastive Language-image Pretraining'
authors: Xiaoyi Dong, Jianmin Bao, Yinglin Zheng, Ting Zhang, Dongdong Chen, Hao Yang,
  Ming Zeng, Weiming Zhang, Lu Yuan, Dong Chen, Fang Wen, Nenghai Yu
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2023
bibkey: dong2022maskclip
citations: 76
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2208.12262'}]
tags: ["CVPR", "Has Code", "Tools", "Training Techniques"]
short_authors: Dong et al.
---
This paper presents a simple yet effective framework MaskCLIP, which
incorporates a newly proposed masked self-distillation into contrastive
language-image pretraining. The core idea of masked self-distillation is to
distill representation from a full image to the representation predicted from a
masked image. Such incorporation enjoys two vital benefits. First, masked
self-distillation targets local patch representation learning, which is
complementary to vision-language contrastive focusing on text-related
representation. Second, masked self-distillation is also consistent with
vision-language contrastive from the perspective of training objective as both
utilize the visual encoder for feature aligning, and thus is able to learn
local semantics getting indirect supervision from the language. We provide
specially designed experiments with a comprehensive analysis to validate the
two benefits. Symmetrically, we also introduce the local semantic supervision
into the text branch, which further improves the pretraining performance. With
extensive experiments, we show that MaskCLIP, when applied to various
challenging downstream tasks, achieves superior results in linear probing,
finetuning, and zero-shot performance with the guidance of the language
encoder. Code will be release at https://github.com/LightDXY/MaskCLIP.