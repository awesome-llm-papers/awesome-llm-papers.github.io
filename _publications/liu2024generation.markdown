---
layout: publication
title: Generation With Dynamic Vocabulary
authors: Liu et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2024
bibkey: liu2024generation
citations: 57
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.08481'}]
tags: [Efficiency And Optimization, AAAI, Applications, Training Techniques]
---
We introduce a new dynamic vocabulary for language models. It can involve
arbitrary text spans during generation. These text spans act as basic
generation bricks, akin to tokens in the traditional static vocabularies. We
show that, the ability to generate multi-tokens atomically improve both
generation quality and efficiency (compared to the standard language model, the
MAUVE metric is increased by 25%, the latency is decreased by 20%). The dynamic
vocabulary can be deployed in a plug-and-play way, thus is attractive for
various downstream applications. For example, we demonstrate that dynamic
vocabulary can be applied to different domains in a training-free manner. It
also helps to generate reliable citations in question answering tasks
(substantially enhancing citation results without compromising answer
accuracy).