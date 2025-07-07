---
layout: publication
title: 'Greedy-layer Pruning: Speeding Up Transformer Models For Natural Language
  Processing'
authors: David Peer, Sebastian Stabinger, Stefan Engl, Antonio Rodriguez-sanchez
conference: Arxiv
year: 2021
citations: 26
bibkey: peer2021greedy
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2105.14839'}, {name: Code,
    url: 'https://github.com/deepopinion/greedy-layer-pruning'}]
tags: [Distillation, Transformer, Training Techniques, Fine-Tuning, Pre-Training,
  Efficiency and Optimization, Has Code, Pruning, Model Architecture]
---
Fine-tuning transformer models after unsupervised pre-training reaches a very
high performance on many different natural language processing tasks.
Unfortunately, transformers suffer from long inference times which greatly
increases costs in production. One possible solution is to use knowledge
distillation, which solves this problem by transferring information from large
teacher models to smaller student models. Knowledge distillation maintains high
performance and reaches high compression rates, nevertheless, the size of the
student model is fixed after pre-training and can not be changed individually
for a given downstream task and use-case to reach a desired performance/speedup
ratio. Another solution to reduce the size of models in a much more
fine-grained and computationally cheaper fashion is to prune layers after the
pre-training. The price to pay is that the performance of layer-wise pruning
algorithms is not on par with state-of-the-art knowledge distillation methods.
In this paper, Greedy-layer pruning is introduced to (1) outperform current
state-of-the-art for layer-wise pruning, (2) close the performance gap when
compared to knowledge distillation, while (3) providing a method to adapt the
model size dynamically to reach a desired performance/speedup tradeoff without
the need of additional pre-training phases. Our source code is available on
https://github.com/deepopinion/greedy-layer-pruning.