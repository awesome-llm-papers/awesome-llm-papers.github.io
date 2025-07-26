---
layout: publication
title: Multimodal Adaptive Distillation For Leveraging Unimodal Encoders For Vision-language
  Tasks
authors: Zhecan Wang, Noel Codella, Yen-chun Chen, Luowei Zhou, Xiyang Dai, Bin Xiao,
  Jianwei Yang, Haoxuan You, Kai-wei Chang, Shih-fu Chang, Lu Yuan
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2022
bibkey: wang2022multimodal
citations: 108
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2204.10496'}]
tags: ["CVPR"]
short_authors: Wang et al.
---
Cross-modal encoders for vision-language (VL) tasks are often pretrained with
carefully curated vision-language datasets. While these datasets reach an order
of 10 million samples, the labor cost is prohibitive to scale further.
Conversely, unimodal encoders are pretrained with simpler annotations that are
less cost-prohibitive, achieving scales of hundreds of millions to billions. As
a result, unimodal encoders have achieved state-of-art (SOTA) on many
downstream tasks. However, challenges remain when applying to VL tasks. The
pretraining data is not optimal for cross-modal architectures and requires
heavy computational resources. In addition, unimodal architectures lack
cross-modal interactions that have demonstrated significant benefits for VL
tasks. Therefore, how to best leverage pretrained unimodal encoders for VL
tasks is still an area of active research. In this work, we propose a method to
leverage unimodal vision and text encoders for VL tasks that augment existing
VL approaches while conserving computational complexity. Specifically, we
propose Multimodal Adaptive Distillation (MAD), which adaptively distills
useful knowledge from pretrained encoders to cross-modal VL encoders. Second,
to better capture nuanced impacts on VL task performance, we introduce an
evaluation protocol that includes Visual Commonsense Reasoning (VCR), Visual
Entailment (SNLI-VE), and Visual Question Answering (VQA), across a variety of
data constraints and conditions of domain shift. Experiments demonstrate that
MAD leads to consistent gains in the low-shot, domain-shifted, and
fully-supervised conditions on VCR, SNLI-VE, and VQA, achieving SOTA
performance on VCR compared to other single models pretrained with image-text
data. Finally, MAD outperforms concurrent works utilizing pretrained vision
encoder from CLIP. Code will be made available.