---
layout: publication
title: Structural Supervision Improves Learning Of Non-local Grammatical Dependencies
authors: Ethan Wilcox, Peng Qian, Richard Futrell, Miguel Ballesteros, Roger Levy
conference: Proceedings of the 2019 Conference of the North
year: 2019
bibkey: wilcox2019structural
citations: 66
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1903.00943'}]
tags: ["Training Techniques"]
short_authors: Wilcox et al.
---
State-of-the-art LSTM language models trained on large corpora learn
sequential contingencies in impressive detail and have been shown to acquire a
number of non-local grammatical dependencies with some success. Here we
investigate whether supervision with hierarchical structure enhances learning
of a range of grammatical dependencies, a question that has previously been
addressed only for subject-verb agreement. Using controlled experimental
methods from psycholinguistics, we compare the performance of word-based LSTM
models versus two models that represent hierarchical structure and deploy it in
left-to-right processing: Recurrent Neural Network Grammars (RNNGs) (Dyer et
al., 2016) and a incrementalized version of the Parsing-as-Language-Modeling
configuration from Chariak et al., (2016). Models are tested on a diverse range
of configurations for two classes of non-local grammatical dependencies in
English---Negative Polarity licensing and Filler--Gap Dependencies. Using the
same training data across models, we find that structurally-supervised models
outperform the LSTM, with the RNNG demonstrating best results on both types of
grammatical dependencies and even learning many of the Island Constraints on
the filler--gap dependency. Structural supervision thus provides data
efficiency advantages over purely string-based training of neural language
models in acquiring human-like generalizations about non-local grammatical
dependencies.