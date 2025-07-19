---
layout: publication
title: Declarative Experimentation In Information Retrieval Using Pyterrier
authors: Macdonald Craig, Tonellotto Nicola
conference: Proceedings of the 2020 ACM SIGIR on International Conference on Theory
  of Information Retrieval
year: 2020
bibkey: macdonald2020declarative
citations: 82
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2007.14271'}]
tags: [Model Architecture, Efficiency And Optimization, Tools, SIGIR]
---
The advent of deep machine learning platforms such as Tensorflow and Pytorch,
developed in expressive high-level languages such as Python, have allowed more
expressive representations of deep neural network architectures. We argue that
such a powerful formalism is missing in information retrieval (IR), and propose
a framework called PyTerrier that allows advanced retrieval pipelines to be
expressed, and evaluated, in a declarative manner close to their conceptual
design. Like the aforementioned frameworks that compile deep learning
experiments into primitive GPU operations, our framework targets IR platforms
as backends in order to execute and evaluate retrieval pipelines. Further, we
can automatically optimise the retrieval pipelines to increase their efficiency
to suite a particular IR platform backend. Our experiments, conducted on TREC
Robust and ClueWeb09 test collections, demonstrate the efficiency benefits of
these optimisations for retrieval pipelines involving both the Anserini and
Terrier IR platforms.