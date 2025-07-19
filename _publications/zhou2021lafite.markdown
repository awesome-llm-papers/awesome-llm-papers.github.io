---
layout: publication
title: 'LAFITE: Towards Language-free Training For Text-to-image Generation'
authors: Zhou et al.
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2021
bibkey: zhou2021lafite
citations: 120
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2111.13792'}]
tags: [RAG, Training Techniques, CVPR, Reinforcement Learning, Fine Tuning, Datasets]
---
One of the major challenges in training text-to-image generation models is
the need of a large number of high-quality image-text pairs. While image
samples are often easily accessible, the associated text descriptions typically
require careful human captioning, which is particularly time- and
cost-consuming. In this paper, we propose the first work to train text-to-image
generation models without any text data. Our method leverages the well-aligned
multi-modal semantic space of the powerful pre-trained CLIP model: the
requirement of text-conditioning is seamlessly alleviated via generating text
features from image features. Extensive experiments are conducted to illustrate
the effectiveness of the proposed method. We obtain state-of-the-art results in
the standard text-to-image generation tasks. Importantly, the proposed
language-free model outperforms most existing models trained with full
image-text pairs. Furthermore, our method can be applied in fine-tuning
pre-trained models, which saves both training time and cost in training
text-to-image generation models. Our pre-trained model obtains competitive
results in zero-shot text-to-image generation on the MS-COCO dataset, yet with
around only 1% of the model size and training data size relative to the
recently proposed large DALL-E model.