---
layout: publication
title: 'Zerocap: Zero-shot Image-to-text Generation For Visual-semantic Arithmetic'
authors: Yoad Tewel, Yoav Shalev, Idan Schwartz, Lior Wolf
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2022
bibkey: tewel2021zerocap
citations: 90
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2111.14447'}]
tags: ["CVPR"]
short_authors: Tewel et al.
---
Recent text-to-image matching models apply contrastive learning to large
corpora of uncurated pairs of images and sentences. While such models can
provide a powerful score for matching and subsequent zero-shot tasks, they are
not capable of generating caption given an image. In this work, we repurpose
such models to generate a descriptive text given an image at inference time,
without any further training or tuning steps. This is done by combining the
visual-semantic model with a large language model, benefiting from the
knowledge in both web-scale models. The resulting captions are much less
restrictive than those obtained by supervised captioning methods. Moreover, as
a zero-shot learning method, it is extremely flexible and we demonstrate its
ability to perform image arithmetic in which the inputs can be either images or
text, and the output is a sentence. This enables novel high-level vision
capabilities such as comparing two images or solving visual analogy tests. Our
code is available at: https://github.com/YoadTew/zero-shot-image-to-text.