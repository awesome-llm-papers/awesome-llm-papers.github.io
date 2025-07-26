---
layout: publication
title: Semantic Sentence Matching With Densely-connected Recurrent And Co-attentive
  Information
authors: Seonhoon Kim, Inho Kang, Nojun Kwak
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2019
bibkey: kim2018semantic
citations: 181
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1805.11360'}]
tags: ["AAAI", "Model Architecture"]
short_authors: Seonhoon Kim, Inho Kang, Nojun Kwak
---
Sentence matching is widely used in various natural language tasks such as
natural language inference, paraphrase identification, and question answering.
For these tasks, understanding logical and semantic relationship between two
sentences is required but it is yet challenging. Although attention mechanism
is useful to capture the semantic relationship and to properly align the
elements of two sentences, previous methods of attention mechanism simply use a
summation operation which does not retain original features enough. Inspired by
DenseNet, a densely connected convolutional network, we propose a
densely-connected co-attentive recurrent neural network, each layer of which
uses concatenated information of attentive features as well as hidden features
of all the preceding recurrent layers. It enables preserving the original and
the co-attentive feature information from the bottommost word embedding layer
to the uppermost recurrent layer. To alleviate the problem of an
ever-increasing size of feature vectors due to dense concatenation operations,
we also propose to use an autoencoder after dense concatenation. We evaluate
our proposed architecture on highly competitive benchmark datasets related to
sentence matching. Experimental results show that our architecture, which
retains recurrent and attentive features, achieves state-of-the-art
performances for most of the tasks.