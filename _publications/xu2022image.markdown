---
layout: publication
title: Image Captioning In The Transformer Age
authors: Xu et al.
conference: Lecture Notes in Computer Science
year: 2022
bibkey: xu2022image
citations: 67
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2204.07374'}]
tags: [Training Techniques, Transformer, Model Architecture, Survey Paper, Reinforcement
    Learning]
---
Image Captioning (IC) has achieved astonishing developments by incorporating
various techniques into the CNN-RNN encoder-decoder architecture. However,
since CNN and RNN do not share the basic network component, such a
heterogeneous pipeline is hard to be trained end-to-end where the visual
encoder will not learn anything from the caption supervision. This drawback
inspires the researchers to develop a homogeneous architecture that facilitates
end-to-end training, for which Transformer is the perfect one that has proven
its huge potential in both vision and language domains and thus can be used as
the basic component of the visual encoder and language decoder in an IC
pipeline. Meantime, self-supervised learning releases the power of the
Transformer architecture that a pre-trained large-scale one can be generalized
to various tasks including IC. The success of these large-scale models seems to
weaken the importance of the single IC task. However, we demonstrate that IC
still has its specific significance in this age by analyzing the connections
between IC with some popular self-supervised learning paradigms. Due to the
page limitation, we only refer to highly important papers in this short survey
and more related works can be found at
https://github.com/SjokerLily/awesome-image-captioning.