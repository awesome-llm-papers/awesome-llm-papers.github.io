---
layout: publication
title: 'Gmail Smart Compose: Real-time Assisted Writing'
authors: Mia Xu Chen et al.
conference: Arxiv
year: 2019
citations: 48
bibkey: chen2019gmail
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.00080'}]
tags: [RAG, Training Techniques]
---
In this paper, we present Smart Compose, a novel system for generating
interactive, real-time suggestions in Gmail that assists users in writing mails
by reducing repetitive typing. In the design and deployment of such a
large-scale and complicated system, we faced several challenges including model
selection, performance evaluation, serving and other practical issues. At the
core of Smart Compose is a large-scale neural language model. We leveraged
state-of-the-art machine learning techniques for language model training which
enabled high-quality suggestion prediction, and constructed novel serving
infrastructure for high-throughput and real-time inference. Experimental
results show the effectiveness of our proposed system design and deployment
approach. This system is currently being served in Gmail.