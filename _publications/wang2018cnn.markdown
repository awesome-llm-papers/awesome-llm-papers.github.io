---
layout: publication
title: 'CNN+CNN: Convolutional Decoders For Image Captioning'
authors: Qingzhong Wang, Antoni B. Chan
conference: Arxiv
year: 2018
bibkey: wang2018cnn
citations: 65
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1805.09019'}]
tags: ["Model Architecture"]
short_authors: Qingzhong Wang, Antoni B. Chan
---
Image captioning is a challenging task that combines the field of computer
vision and natural language processing. A variety of approaches have been
proposed to achieve the goal of automatically describing an image, and
recurrent neural network (RNN) or long-short term memory (LSTM) based models
dominate this field. However, RNNs or LSTMs cannot be calculated in parallel
and ignore the underlying hierarchical structure of a sentence. In this paper,
we propose a framework that only employs convolutional neural networks (CNNs)
to generate captions. Owing to parallel computing, our basic model is around 3
times faster than NIC (an LSTM-based model) during training time, while also
providing better results. We conduct extensive experiments on MSCOCO and
investigate the influence of the model width and depth. Compared with
LSTM-based models that apply similar attention mechanisms, our proposed models
achieves comparable scores of BLEU-1,2,3,4 and METEOR, and higher scores of
CIDEr. We also test our model on the paragraph annotation dataset, and get
higher CIDEr score compared with hierarchical LSTMs