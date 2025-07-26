---
layout: publication
title: Engaging Image Captioning Via Personality
authors: Kurt Shuster, Samuel Humeau, Hexiang Hu, Antoine Bordes, Jason Weston
conference: 2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2019
bibkey: shuster2018engaging
citations: 164
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1810.10665'}]
tags: ["CVPR"]
short_authors: Shuster et al.
---
Standard image captioning tasks such as COCO and Flickr30k are factual,
neutral in tone and (to a human) state the obvious (e.g., "a man playing a
guitar"). While such tasks are useful to verify that a machine understands the
content of an image, they are not engaging to humans as captions. With this in
mind we define a new task, Personality-Captions, where the goal is to be as
engaging to humans as possible by incorporating controllable style and
personality traits. We collect and release a large dataset of 201,858 of such
captions conditioned over 215 possible traits. We build models that combine
existing work from (i) sentence representations (Mazare et al., 2018) with
Transformers trained on 1.7 billion dialogue examples; and (ii) image
representations (Mahajan et al., 2018) with ResNets trained on 3.5 billion
social media images. We obtain state-of-the-art performance on Flickr30k and
COCO, and strong performance on our new task. Finally, online evaluations
validate that our task and models are engaging to humans, with our best model
close to human performance.