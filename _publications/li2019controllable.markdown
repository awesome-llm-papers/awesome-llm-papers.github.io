---
layout: publication
title: Controllable Text-to-image Generation
authors: Bowen Li, Xiaojuan Qi, Thomas Lukasiewicz, Philip H. S. Torr
conference: Arxiv
year: 2019
bibkey: li2019controllable
citations: 143
additional_links: [{name: Code, url: 'https://github.com/mrlibw/ControlGAN'}, {name: Paper,
    url: 'https://arxiv.org/abs/1909.07083'}]
tags: ["Datasets", "Evaluation", "Has Code", "Security", "Training Techniques"]
short_authors: Li et al.
---
In this paper, we propose a novel controllable text-to-image generative
adversarial network (ControlGAN), which can effectively synthesise high-quality
images and also control parts of the image generation according to natural
language descriptions. To achieve this, we introduce a word-level spatial and
channel-wise attention-driven generator that can disentangle different visual
attributes, and allow the model to focus on generating and manipulating
subregions corresponding to the most relevant words. Also, a word-level
discriminator is proposed to provide fine-grained supervisory feedback by
correlating words with image regions, facilitating training an effective
generator which is able to manipulate specific visual attributes without
affecting the generation of other content. Furthermore, perceptual loss is
adopted to reduce the randomness involved in the image generation, and to
encourage the generator to manipulate specific attributes required in the
modified text. Extensive experiments on benchmark datasets demonstrate that our
method outperforms existing state of the art, and is able to effectively
manipulate synthetic images using natural language descriptions. Code is
available at https://github.com/mrlibw/ControlGAN.