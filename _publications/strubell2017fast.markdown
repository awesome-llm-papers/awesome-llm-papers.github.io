---
layout: publication
title: Fast And Accurate Entity Recognition With Iterated Dilated Convolutions
authors: Emma Strubell, Patrick Verga, David Belanger, Andrew Mccallum
conference: Proceedings of the 2017 Conference on Empirical Methods in Natural Language
  Processing
year: 2017
bibkey: strubell2017fast
citations: 464
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1702.02098'}]
tags: ["EMNLP", "Efficiency", "Model Architecture"]
short_authors: Strubell et al.
---
Today when many practitioners run basic NLP on the entire web and
large-volume traffic, faster methods are paramount to saving time and energy
costs. Recent advances in GPU hardware have led to the emergence of
bi-directional LSTMs as a standard method for obtaining per-token vector
representations serving as input to labeling tasks such as NER (often followed
by prediction in a linear-chain CRF). Though expressive and accurate, these
models fail to fully exploit GPU parallelism, limiting their computational
efficiency. This paper proposes a faster alternative to Bi-LSTMs for NER:
Iterated Dilated Convolutional Neural Networks (ID-CNNs), which have better
capacity than traditional CNNs for large context and structured prediction.
Unlike LSTMs whose sequential processing on sentences of length N requires O(N)
time even in the face of parallelism, ID-CNNs permit fixed-depth convolutions
to run in parallel across entire documents. We describe a distinct combination
of network structure, parameter sharing and training procedures that enable
dramatic 14-20x test-time speedups while retaining accuracy comparable to the
Bi-LSTM-CRF. Moreover, ID-CNNs trained to aggregate context from the entire
document are even more accurate while maintaining 8x faster test time speeds.