---
layout: publication
title: An Empirical Evaluation Of Generic Convolutional And Recurrent Networks For
  Sequence Modeling
authors: Shaojie Bai, J. Zico Kolter, Vladlen Koltun
conference: Arxiv
year: 2018
bibkey: bai2018empirical
citations: 3968
additional_links: [{name: Code, url: 'http://github.com/locuslab/TCN'}, {name: Paper,
    url: 'https://arxiv.org/abs/1803.01271'}]
tags: ["Evaluation", "Model Architecture"]
short_authors: Shaojie Bai, J. Zico Kolter, Vladlen Koltun
---
For most deep learning practitioners, sequence modeling is synonymous with
recurrent networks. Yet recent results indicate that convolutional
architectures can outperform recurrent networks on tasks such as audio
synthesis and machine translation. Given a new sequence modeling task or
dataset, which architecture should one use? We conduct a systematic evaluation
of generic convolutional and recurrent architectures for sequence modeling. The
models are evaluated across a broad range of standard tasks that are commonly
used to benchmark recurrent networks. Our results indicate that a simple
convolutional architecture outperforms canonical recurrent networks such as
LSTMs across a diverse range of tasks and datasets, while demonstrating longer
effective memory. We conclude that the common association between sequence
modeling and recurrent networks should be reconsidered, and convolutional
networks should be regarded as a natural starting point for sequence modeling
tasks. To assist related work, we have made code available at
http://github.com/locuslab/TCN .