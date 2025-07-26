---
layout: publication
title: Incorporating Copying Mechanism In Image Captioning For Learning Novel Objects
authors: Ting Yao, Yingwei Pan, Yehao Li, Tao Mei
conference: 2017 IEEE Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2017
bibkey: yao2017incorporating
citations: 152
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1708.05271'}]
tags: ["CVPR", "Model Architecture", "Training Techniques"]
short_authors: Yao et al.
---
Image captioning often requires a large set of training image-sentence pairs.
In practice, however, acquiring sufficient training pairs is always expensive,
making the recent captioning models limited in their ability to describe
objects outside of training corpora (i.e., novel objects). In this paper, we
present Long Short-Term Memory with Copying Mechanism (LSTM-C) --- a new
architecture that incorporates copying into the Convolutional Neural Networks
(CNN) plus Recurrent Neural Networks (RNN) image captioning framework, for
describing novel objects in captions. Specifically, freely available object
recognition datasets are leveraged to develop classifiers for novel objects.
Our LSTM-C then nicely integrates the standard word-by-word sentence generation
by a decoder RNN with copying mechanism which may instead select words from
novel objects at proper places in the output sentence. Extensive experiments
are conducted on both MSCOCO image captioning and ImageNet datasets,
demonstrating the ability of our proposed LSTM-C architecture to describe novel
objects. Furthermore, superior results are reported when compared to
state-of-the-art deep models.