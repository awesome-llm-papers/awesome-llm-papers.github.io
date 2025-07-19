---
layout: publication
title: 'Rethinking Experience Replay: A Bag Of Tricks For Continual Learning'
authors: Buzzega et al.
conference: 2020 25th International Conference on Pattern Recognition (ICPR)
year: 2020
bibkey: buzzega2020rethinking
citations: 68
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.05595'}]
tags: [Datasets]
---
In Continual Learning, a Neural Network is trained on a stream of data whose
distribution shifts over time. Under these assumptions, it is especially
challenging to improve on classes appearing later in the stream while remaining
accurate on previous ones. This is due to the infamous problem of catastrophic
forgetting, which causes a quick performance degradation when the classifier
focuses on learning new categories. Recent literature proposed various
approaches to tackle this issue, often resorting to very sophisticated
techniques. In this work, we show that naive rehearsal can be patched to
achieve similar performance. We point out some shortcomings that restrain
Experience Replay (ER) and propose five tricks to mitigate them. Experiments
show that ER, thus enhanced, displays an accuracy gain of 51.2 and 26.9
percentage points on the CIFAR-10 and CIFAR-100 datasets respectively (memory
buffer size 1000). As a result, it surpasses current state-of-the-art
rehearsal-based methods.