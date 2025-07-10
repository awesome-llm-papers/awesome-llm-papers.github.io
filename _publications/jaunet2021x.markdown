---
layout: publication
title: 'Visqa: X-raying Vision And Language Reasoning In Transformers'
authors: Theo Jaunet et al.
conference: IEEE Transactions on Visualization and Computer Graphics
year: 2021
citations: 16
bibkey: jaunet2021x
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.00926'}]
tags: [Model Architecture, Attention Mechanism, Ethics and Bias, Transformer, ACL,
  Reinforcement Learning, Multimodal Models, Training Techniques, Evaluation]
---
Visual Question Answering systems target answering open-ended textual
questions given input images. They are a testbed for learning high-level
reasoning with a primary use in HCI, for instance assistance for the visually
impaired. Recent research has shown that state-of-the-art models tend to
produce answers exploiting biases and shortcuts in the training data, and
sometimes do not even look at the input image, instead of performing the
required reasoning steps. We present VisQA, a visual analytics tool that
explores this question of reasoning vs. bias exploitation. It exposes the key
element of state-of-the-art neural models -- attention maps in transformers.
Our working hypothesis is that reasoning steps leading to model predictions are
observable from attention distributions, which are particularly useful for
visualization. The design process of VisQA was motivated by well-known bias
examples from the fields of deep learning and vision-language reasoning and
evaluated in two ways. First, as a result of a collaboration of three fields,
machine learning, vision and language reasoning, and data analytics, the work
lead to a better understanding of bias exploitation of neural models for VQA,
which eventually resulted in an impact on its design and training through the
proposition of a method for the transfer of reasoning patterns from an oracle
model. Second, we also report on the design of VisQA, and a goal-oriented
evaluation of VisQA targeting the analysis of a model decision process from
multiple experts, providing evidence that it makes the inner workings of models
accessible to users.