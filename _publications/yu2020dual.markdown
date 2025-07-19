---
layout: publication
title: Dual Attention On Pyramid Feature Maps For Image Captioning
authors: Yu Litao, Zhang Jian, Wu Qiang
conference: IEEE Transactions on Multimedia
year: 2020
bibkey: yu2020dual
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2011.01385'}]
tags: [Datasets, Model Architecture, Attention Mechanism]
---
Generating natural sentences from images is a fundamental learning task for
visual-semantic understanding in multimedia. In this paper, we propose to apply
dual attention on pyramid image feature maps to fully explore the
visual-semantic correlations and improve the quality of generated sentences.
Specifically, with the full consideration of the contextual information
provided by the hidden state of the RNN controller, the pyramid attention can
better localize the visually indicative and semantically consistent regions in
images. On the other hand, the contextual information can help re-calibrate the
importance of feature components by learning the channel-wise dependencies, to
improve the discriminative power of visual features for better content
description. We conducted comprehensive experiments on three well-known
datasets: Flickr8K, Flickr30K and MS COCO, which achieved impressive results in
generating descriptive and smooth natural sentences from images. Using either
convolution visual features or more informative bottom-up attention features,
our composite captioning model achieves very promising performance in a
single-model mode. The proposed pyramid attention and dual attention methods
are highly modular, which can be inserted into various image captioning modules
to further improve the performance.