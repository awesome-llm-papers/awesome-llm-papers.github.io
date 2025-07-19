---
layout: publication
title: An End-to-end Textspotter With Explicit Alignment And Attention
authors: He et al.
conference: 2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition
year: 2018
bibkey: he2018end
citations: 229
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1803.03474'}]
tags: [Training Techniques, Attention Mechanism, Tools, CVPR, Transformer, Model Architecture,
  Datasets]
---
Text detection and recognition in natural images have long been considered as
two separate tasks that are processed sequentially. Training of two tasks in a
unified framework is non-trivial due to significant dif- ferences in
optimisation difficulties. In this work, we present a conceptually simple yet
efficient framework that simultaneously processes the two tasks in one shot.
Our main contributions are three-fold: 1) we propose a novel text-alignment
layer that allows it to precisely compute convolutional features of a text
instance in ar- bitrary orientation, which is the key to boost the per-
formance; 2) a character attention mechanism is introduced by using character
spatial information as explicit supervision, leading to large improvements in
recognition; 3) two technologies, together with a new RNN branch for word
recognition, are integrated seamlessly into a single model which is end-to-end
trainable. This allows the two tasks to work collaboratively by shar- ing
convolutional features, which is critical to identify challenging text
instances. Our model achieves impressive results in end-to-end recognition on
the ICDAR2015 dataset, significantly advancing most recent results, with
improvements of F-measure from (0.54, 0.51, 0.47) to (0.82, 0.77, 0.63), by
using a strong, weak and generic lexicon respectively. Thanks to joint
training, our method can also serve as a good detec- tor by achieving a new
state-of-the-art detection performance on two datasets.