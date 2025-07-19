---
layout: publication
title: 'Superneurons: Dynamic GPU Memory Management For Training Deep Neural Networks'
authors: Wang et al.
conference: Arxiv
year: 2018
bibkey: wang2018superneurons
citations: 114
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1801.04380'}]
tags: [Training Techniques, Evaluation, Model Architecture, Efficiency And Optimization,
  Reinforcement Learning]
---
Going deeper and wider in neural architectures improves the accuracy, while
the limited GPU DRAM places an undesired restriction on the network design
domain. Deep Learning (DL) practitioners either need change to less desired
network architectures, or nontrivially dissect a network across multiGPUs.
These distract DL practitioners from concentrating on their original machine
learning tasks. We present SuperNeurons: a dynamic GPU memory scheduling
runtime to enable the network training far beyond the GPU DRAM capacity.
SuperNeurons features 3 memory optimizations, \textit\{Liveness Analysis\},
\textit\{Unified Tensor Pool\}, and \textit\{Cost-Aware Recomputation\}, all
together they effectively reduce the network-wide peak memory usage down to the
maximal memory usage among layers. We also address the performance issues in
those memory saving techniques. Given the limited GPU DRAM, SuperNeurons not
only provisions the necessary memory for the training, but also dynamically
allocates the memory for convolution workspaces to achieve the high
performance. Evaluations against Caffe, Torch, MXNet and TensorFlow have
demonstrated that SuperNeurons trains at least 3.2432 deeper network than
current ones with the leading performance. Particularly, SuperNeurons can train
ResNet2500 that has \\(10^4\\) basic network layers on a 12GB K40c.