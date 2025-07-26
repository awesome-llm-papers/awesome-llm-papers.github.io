---
layout: publication
title: Recursive Recurrent Nets With Attention Modeling For OCR In The Wild
authors: Chen-yu Lee, Simon Osindero
conference: 2016 IEEE Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2016
bibkey: lee2016recursive
citations: 454
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1603.03101'}]
tags: ["CVPR", "Model Architecture"]
short_authors: Chen-yu Lee, Simon Osindero
---
We present recursive recurrent neural networks with attention modeling
(R\\(^2\\)AM) for lexicon-free optical character recognition in natural scene
images. The primary advantages of the proposed method are: (1) use of recursive
convolutional neural networks (CNNs), which allow for parametrically efficient
and effective image feature extraction; (2) an implicitly learned
character-level language model, embodied in a recurrent neural network which
avoids the need to use N-grams; and (3) the use of a soft-attention mechanism,
allowing the model to selectively exploit image features in a coordinated way,
and allowing for end-to-end training within a standard backpropagation
framework. We validate our method with state-of-the-art performance on
challenging benchmark datasets: Street View Text, IIIT5k, ICDAR and Synth90k.