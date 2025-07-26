---
layout: publication
title: 'CLIP-GEN: Language-free Training Of A Text-to-image Generator With CLIP'
authors: Zihao Wang, Wei Liu, Qian He, Xinglong Wu, Zili Yi
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2022
bibkey: wang2022clip
citations: 231
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.00386'}]
tags: ["CVPR", "Model Architecture", "Training Techniques"]
short_authors: Wang et al.
---
Training a text-to-image generator in the general domain (e.g., Dall.e,
CogView) requires huge amounts of paired text-image data, which is too
expensive to collect. In this paper, we propose a self-supervised scheme named
as CLIP-GEN for general text-to-image generation with the language-image priors
extracted with a pre-trained CLIP model. In our approach, we only require a set
of unlabeled images in the general domain to train a text-to-image generator.
Specifically, given an image without text labels, we first extract the
embedding of the image in the united language-vision embedding space with the
image encoder of CLIP. Next, we convert the image into a sequence of discrete
tokens in the VQGAN codebook space (the VQGAN model can be trained with the
unlabeled image dataset in hand). Finally, we train an autoregressive
transformer that maps the image tokens from its unified language-vision
representation. Once trained, the transformer can generate coherent image
tokens based on the text embedding extracted from the text encoder of CLIP upon
an input text. Such a strategy enables us to train a strong and general
text-to-image generator with large text-free image dataset such as ImageNet.
Qualitative and quantitative evaluations verify that our method significantly
outperforms optimization-based text-to-image methods in terms of image quality
while not compromising the text-image matching. Our method can even achieve
comparable performance as flagship supervised models like CogView.