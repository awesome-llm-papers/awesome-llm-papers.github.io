---
layout: publication
title: Compressing Recurrent Neural Network With Tensor Train
authors: Andros Tjandra, Sakriani Sakti, Satoshi Nakamura
conference: 2017 International Joint Conference on Neural Networks (IJCNN)
year: 2017
bibkey: tjandra2017compressing
citations: 87
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1705.08052'}]
tags: ["Training Techniques"]
short_authors: Andros Tjandra, Sakriani Sakti, Satoshi Nakamura
---
Recurrent Neural Network (RNN) are a popular choice for modeling temporal and
sequential tasks and achieve many state-of-the-art performance on various
complex problems. However, most of the state-of-the-art RNNs have millions of
parameters and require many computational resources for training and predicting
new data. This paper proposes an alternative RNN model to reduce the number of
parameters significantly by representing the weight parameters based on Tensor
Train (TT) format. In this paper, we implement the TT-format representation for
several RNN architectures such as simple RNN and Gated Recurrent Unit (GRU). We
compare and evaluate our proposed RNN model with uncompressed RNN model on
sequence classification and sequence prediction tasks. Our proposed RNNs with
TT-format are able to preserve the performance while reducing the number of RNN
parameters significantly up to 40 times smaller.