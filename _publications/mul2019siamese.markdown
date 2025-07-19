---
layout: publication
title: Siamese Recurrent Networks Learn First-order Logic Reasoning And Exhibit Zero-shot
  Compositional Generalization
authors: Mul Mathijs, Zuidema Willem
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2019
bibkey: mul2019siamese
citations: 62
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.00180'}]
tags: [Model Architecture, CVPR, Datasets]
---
Can neural nets learn logic? We approach this classic question with current
methods, and demonstrate that recurrent neural networks can learn to recognize
first order logical entailment relations between expressions. We define an
artificial language in first-order predicate logic, generate a large dataset of
sample 'sentences', and use an automatic theorem prover to infer the relation
between random pairs of such sentences. We describe a Siamese neural
architecture trained to predict the logical relation, and experiment with
recurrent and recursive networks. Siamese Recurrent Networks are surprisingly
successful at the entailment recognition task, reaching near perfect
performance on novel sentences (consisting of known words), and even
outperforming recursive networks. We report a series of experiments to test the
ability of the models to perform compositional generalization. In particular,
we study how they deal with sentences of unseen length, and sentences
containing unseen words. We show that set-ups using LSTMs and GRUs obtain high
scores on these tests, demonstrating a form of compositionality.