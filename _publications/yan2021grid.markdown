---
layout: publication
title: 'Grid-vlp: Revisiting Grid Features For Vision-language Pre-training'
authors: Yan et al.
conference: Machine Intelligence Research
year: 2021
bibkey: yan2021grid
citations: 134
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2108.09479'}]
tags: [Training Techniques, Transformer, Model Architecture, Efficiency And Optimization,
  Reinforcement Learning, Multimodal Models, Datasets, Merging]
---
Existing approaches to vision-language pre-training (VLP) heavily rely on an
object detector based on bounding boxes (regions), where salient objects are
first detected from images and then a Transformer-based model is used for
cross-modal fusion. Despite their superior performance, these approaches are
bounded by the capability of the object detector in terms of both effectiveness
and efficiency. Besides, the presence of object detection imposes unnecessary
constraints on model designs and makes it difficult to support end-to-end
training. In this paper, we revisit grid-based convolutional features for
vision-language pre-training, skipping the expensive region-related steps. We
propose a simple yet effective grid-based VLP method that works surprisingly
well with the grid features. By pre-training only with in-domain datasets, the
proposed Grid-VLP method can outperform most competitive region-based VLP
methods on three examined vision-language understanding tasks. We hope that our
findings help to further advance the state of the art of vision-language
pre-training, and provide a new direction towards effective and efficient VLP.