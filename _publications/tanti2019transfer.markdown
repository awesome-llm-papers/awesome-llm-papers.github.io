---
layout: publication
title: 'Transfer Learning From Language Models To Image Caption Generators: Better
  Models May Not Transfer Better'
authors: Tanti Marc, Gatt Albert, Camilleri Kenneth P.
conference: 2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2019
bibkey: tanti2019transfer
citations: 668
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1901.01216'}]
tags: [Training Techniques, CVPR, Fine Tuning, Datasets]
---
When designing a neural caption generator, a convolutional neural network can
be used to extract image features. Is it possible to also use a neural language
model to extract sentence prefix features? We answer this question by trying
different ways to transfer the recurrent neural network and embedding layer
from a neural language model to an image caption generator. We find that image
caption generators with transferred parameters perform better than those
trained from scratch, even when simply pre-training them on the text of the
same captions dataset it will later be trained on. We also find that the best
language models (in terms of perplexity) do not result in the best caption
generators after transfer learning.