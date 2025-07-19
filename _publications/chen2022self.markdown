---
layout: publication
title: Self-attentive Sequential Recommendation With Cheap Causal Convolutions
authors: Chen et al.
conference: 2018 IEEE International Conference on Data Mining (ICDM)
year: 2022
bibkey: chen2022self
citations: 1704
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2211.01297'}]
tags: [Attention Mechanism, Evaluation, Transformer, Model Architecture, Datasets]
---
Sequential Recommendation is a prominent topic in current research, which
uses user behavior sequence as an input to predict future behavior. By
assessing the correlation strength of historical behavior through the dot
product, the model based on the self-attention mechanism can capture the
long-term preference of the sequence. However, it has two limitations. On the
one hand, it does not effectively utilize the items' local context information
when determining the attention and creating the sequence representation. On the
other hand, the convolution and linear layers often contain redundant
information, which limits the ability to encode sequences. In this paper, we
propose a self-attentive sequential recommendation model based on cheap causal
convolution. It utilizes causal convolutions to capture items' local
information for calculating attention and generating sequence embedding. It
also uses cheap convolutions to improve the representations by lightweight
structure. We evaluate the effectiveness of the proposed model in terms of both
accurate and calibrated sequential recommendation. Experiments on benchmark
datasets show that the proposed model can perform better in single- and
multi-objective recommendation scenarios.