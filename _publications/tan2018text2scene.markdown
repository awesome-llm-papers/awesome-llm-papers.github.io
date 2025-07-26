---
layout: publication
title: 'Text2scene: Generating Compositional Scenes From Textual Descriptions'
authors: Fuwen Tan, Song Feng, Vicente Ordonez
conference: 2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2019
bibkey: tan2018text2scene
citations: 94
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1809.01110'}]
tags: ["CVPR"]
short_authors: Fuwen Tan, Song Feng, Vicente Ordonez
---
In this paper, we propose Text2Scene, a model that generates various forms of
compositional scene representations from natural language descriptions. Unlike
recent works, our method does NOT use Generative Adversarial Networks (GANs).
Text2Scene instead learns to sequentially generate objects and their attributes
(location, size, appearance, etc) at every time step by attending to different
parts of the input text and the current status of the generated scene. We show
that under minor modifications, the proposed framework can handle the
generation of different forms of scene representations, including cartoon-like
scenes, object layouts corresponding to real images, and synthetic images. Our
method is not only competitive when compared with state-of-the-art GAN-based
methods using automatic metrics and superior based on human judgments but also
has the advantage of producing interpretable results.