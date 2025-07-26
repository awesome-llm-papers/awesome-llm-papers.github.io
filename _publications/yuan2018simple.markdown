---
layout: publication
title: A Simple Convolutional Generative Network For Next Item Recommendation
authors: Fajie Yuan, Alexandros Karatzoglou, Ioannis Arapakis, Joemon M Jose, Xiangnan
  He
conference: Proceedings of the Twelfth ACM International Conference on Web Search
  and Data Mining
year: 2019
bibkey: yuan2018simple
citations: 498
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1808.05163'}]
tags: ["Model Architecture"]
short_authors: Yuan et al.
---
Convolutional Neural Networks (CNNs) have been recently introduced in the
domain of session-based next item recommendation. An ordered collection of past
items the user has interacted with in a session (or sequence) are embedded into
a 2-dimensional latent matrix, and treated as an image. The convolution and
pooling operations are then applied to the mapped item embeddings. In this
paper, we first examine the typical session-based CNN recommender and show that
both the generative model and network architecture are suboptimal when modeling
long-range dependencies in the item sequence. To address the issues, we
introduce a simple, but very effective generative model that is capable of
learning high-level representation from both short- and long-range item
dependencies. The network architecture of the proposed model is formed of a
stack of *holed* convolutional layers, which can efficiently increase the
receptive fields without relying on the pooling operation. Another contribution
is the effective use of residual block structure in recommender systems, which
can ease the optimization for much deeper networks. The proposed generative
model attains state-of-the-art accuracy with less training time in the next
item recommendation task. It accordingly can be used as a powerful
recommendation baseline to beat in future, especially when there are long
sequences of user feedback.