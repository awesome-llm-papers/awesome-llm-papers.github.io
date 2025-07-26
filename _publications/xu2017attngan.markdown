---
layout: publication
title: 'Attngan: Fine-grained Text To Image Generation With Attentional Generative
  Adversarial Networks'
authors: Tao Xu, Pengchuan Zhang, Qiuyuan Huang, Han Zhang, Zhe Gan, Xiaolei Huang,
  Xiaodong He
conference: 2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition
year: 2018
bibkey: xu2017attngan
citations: 1697
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1711.10485'}]
tags: ["CVPR", "Model Architecture"]
short_authors: Xu et al.
---
In this paper, we propose an Attentional Generative Adversarial Network
(AttnGAN) that allows attention-driven, multi-stage refinement for fine-grained
text-to-image generation. With a novel attentional generative network, the
AttnGAN can synthesize fine-grained details at different subregions of the
image by paying attentions to the relevant words in the natural language
description. In addition, a deep attentional multimodal similarity model is
proposed to compute a fine-grained image-text matching loss for training the
generator. The proposed AttnGAN significantly outperforms the previous state of
the art, boosting the best reported inception score by 14.14% on the CUB
dataset and 170.25% on the more challenging COCO dataset. A detailed analysis
is also performed by visualizing the attention layers of the AttnGAN. It for
the first time shows that the layered attentional GAN is able to automatically
select the condition at the word level for generating different parts of the
image.