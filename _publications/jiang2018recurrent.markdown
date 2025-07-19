---
layout: publication
title: Recurrent Fusion Network For Image Captioning
authors: Jiang et al.
conference: Lecture Notes in Computer Science
year: 2018
bibkey: jiang2018recurrent
citations: 299
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1807.09986'}]
tags: [Tools, Datasets, Merging]
---
Recently, much advance has been made in image captioning, and an
encoder-decoder framework has been adopted by all the state-of-the-art models.
Under this framework, an input image is encoded by a convolutional neural
network (CNN) and then translated into natural language with a recurrent neural
network (RNN). The existing models counting on this framework merely employ one
kind of CNNs, e.g., ResNet or Inception-X, which describe image contents from
only one specific view point. Thus, the semantic meaning of an input image
cannot be comprehensively understood, which restricts the performance of
captioning. In this paper, in order to exploit the complementary information
from multiple encoders, we propose a novel Recurrent Fusion Network (RFNet) for
tackling image captioning. The fusion process in our model can exploit the
interactions among the outputs of the image encoders and then generate new
compact yet informative representations for the decoder. Experiments on the
MSCOCO dataset demonstrate the effectiveness of our proposed RFNet, which sets
a new state-of-the-art for image captioning.