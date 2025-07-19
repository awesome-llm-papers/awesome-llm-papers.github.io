---
layout: publication
title: Putting Humans In The Image Captioning Loop
authors: Anagnostopoulou Aliki, Hartmann Mareike, Sonntag Daniel
conference: 2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2023
bibkey: anagnostopoulou2023putting
citations: 61
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2306.03476'}]
tags: [CVPR, Training Techniques, Datasets]
---
Image Captioning (IC) models can highly benefit from human feedback in the
training process, especially in cases where data is limited. We present
work-in-progress on adapting an IC system to integrate human feedback, with the
goal to make it easily adaptable to user-specific data. Our approach builds on
a base IC model pre-trained on the MS COCO dataset, which generates captions
for unseen images. The user will then be able to offer feedback on the image
and the generated/predicted caption, which will be augmented to create
additional training instances for the adaptation of the model. The additional
instances are integrated into the model using step-wise updates, and a sparse
memory replay component is used to avoid catastrophic forgetting. We hope that
this approach, while leading to improved results, will also result in
customizable IC models.