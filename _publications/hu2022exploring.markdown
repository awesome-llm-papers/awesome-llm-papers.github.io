---
layout: publication
title: Exploring The Sequence Length Bottleneck In The Transformer For Image Captioning
authors: Hu Jia Cheng, Cavicchioli Roberto, Capotondi Alessandro
conference: Lecture Notes in Computer Science
year: 2022
bibkey: hu2022exploring
citations: 67
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2207.03327'}]
tags: [Training Techniques, Evaluation, Transformer, Model Architecture, Efficiency
    And Optimization, Time Series]
---
Most recent state of the art architectures rely on combinations and
variations of three approaches: convolutional, recurrent and self-attentive
methods. Our work attempts in laying the basis for a new research direction for
sequence modeling based upon the idea of modifying the sequence length. In
order to do that, we propose a new method called "Expansion Mechanism" which
transforms either dynamically or statically the input sequence into a new one
featuring a different sequence length. Furthermore, we introduce a novel
architecture that exploits such method and achieves competitive performances on
the MS-COCO 2014 data set, yielding 134.6 and 131.4 CIDEr-D on the Karpathy
test split in the ensemble and single model configuration respectively and 130
CIDEr-D in the official online evaluation server, despite being neither
recurrent nor fully attentive. At the same time we address the efficiency
aspect in our design and introduce a convenient training strategy suitable for
most computational resources in contrast to the standard one. Source code is
available at https://github.com/jchenghu/exploring