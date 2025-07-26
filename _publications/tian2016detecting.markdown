---
layout: publication
title: Detecting Text In Natural Image With Connectionist Text Proposal Network
authors: Zhi Tian, Weilin Huang, Tong He, Pan He, Yu Qiao
conference: Lecture Notes in Computer Science
year: 2016
bibkey: tian2016detecting
citations: 1025
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1609.03605'}]
tags: []
short_authors: Tian et al.
---
We propose a novel Connectionist Text Proposal Network (CTPN) that accurately
localizes text lines in natural image. The CTPN detects a text line in a
sequence of fine-scale text proposals directly in convolutional feature maps.
We develop a vertical anchor mechanism that jointly predicts location and
text/non-text score of each fixed-width proposal, considerably improving
localization accuracy. The sequential proposals are naturally connected by a
recurrent neural network, which is seamlessly incorporated into the
convolutional network, resulting in an end-to-end trainable model. This allows
the CTPN to explore rich context information of image, making it powerful to
detect extremely ambiguous text. The CTPN works reliably on multi-scale and
multi- language text without further post-processing, departing from previous
bottom-up methods requiring multi-step post-processing. It achieves 0.88 and
0.61 F-measure on the ICDAR 2013 and 2015 benchmarks, surpass- ing recent
results [8, 35] by a large margin. The CTPN is computationally efficient with
0:14s/image, by using the very deep VGG16 model [27]. Online demo is available
at: http://textdet.com/.