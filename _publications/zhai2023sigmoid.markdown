---
layout: publication
title: Sigmoid Loss For Language Image Pre-training
authors: Xiaohua Zhai, Basil Mustafa, Alexander Kolesnikov, Lucas Beyer
conference: 2023 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2023
bibkey: zhai2023sigmoid
citations: 123
additional_links: [{name: Code, url: 'https://github.com/google-research/big_vision'},
  {name: Paper, url: 'https://arxiv.org/abs/2303.15343'}]
tags: ["ICCV", "Training Techniques"]
short_authors: Zhai et al.
---
We propose a simple pairwise Sigmoid loss for Language-Image Pre-training
(SigLIP). Unlike standard contrastive learning with softmax normalization, the
sigmoid loss operates solely on image-text pairs and does not require a global
view of the pairwise similarities for normalization. The sigmoid loss
simultaneously allows further scaling up the batch size, while also performing
better at smaller batch sizes. Combined with Locked-image Tuning, with only
four TPUv4 chips, we train a SigLiT model that achieves 84.5% ImageNet
zero-shot accuracy in two days. The disentanglement of the batch size from the
loss further allows us to study the impact of examples vs pairs and negative to
positive ratio. Finally, we push the batch size to the extreme, up to one
million, and find that the benefits of growing batch size quickly diminish,
with a more reasonable batch size of 32k being sufficient. We release our
models at https://github.com/google-research/big_vision and hope our research
motivates further explorations in improving the quality and efficiency of
language-image pre-training.