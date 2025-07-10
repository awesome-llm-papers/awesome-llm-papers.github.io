---
layout: publication
title: Learning To Few-shot Learn Across Diverse Natural Language Classification Tasks
authors: Trapit Bansal, Rishikesh Jha, Andrew Mccallum
conference: Proceedings of the 28th International Conference on Computational Linguistics
year: 2019
citations: 21
bibkey: bansal2019learning
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.03863'}]
tags: [Model Architecture, Transformer, Fine-Tuning, RAG, Few-Shot, Pre-Training,
  Efficiency and Optimization, Training Techniques]
---
Self-supervised pre-training of transformer models has shown enormous success
in improving performance on a number of downstream tasks. However, fine-tuning
on a new task still requires large amounts of task-specific labelled data to
achieve good performance. We consider this problem of learning to generalize to
new tasks with few examples as a meta-learning problem. While meta-learning has
shown tremendous progress in recent years, its application is still limited to
simulated problems or problems with limited diversity across tasks. We develop
a novel method, LEOPARD, which enables optimization-based meta-learning across
tasks with different number of classes, and evaluate different methods on
generalization to diverse NLP classification tasks. LEOPARD is trained with the
state-of-the-art transformer architecture and shows better generalization to
tasks not seen at all during training, with as few as 4 examples per label.
Across 17 NLP tasks, including diverse domains of entity typing, natural
language inference, sentiment analysis, and several other text classification
tasks, we show that LEOPARD learns better initial parameters for few-shot
learning than self-supervised pre-training or multi-task training,
outperforming many strong baselines, for example, yielding 14.5% average
relative gain in accuracy on unseen tasks with only 4 examples per label.