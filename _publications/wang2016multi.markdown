---
layout: publication
title: Multi-perspective Context Matching For Machine Comprehension
authors: Zhiguo Wang, Haitao Mi, Wael Hamza, Radu Florian
conference: Arxiv
year: 2016
bibkey: wang2016multi
citations: 119
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1612.04211'}]
tags: ["Model Architecture"]
short_authors: Wang et al.
---
Previous machine comprehension (MC) datasets are either too small to train
end-to-end deep learning models, or not difficult enough to evaluate the
ability of current MC techniques. The newly released SQuAD dataset alleviates
these limitations, and gives us a chance to develop more realistic MC models.
Based on this dataset, we propose a Multi-Perspective Context Matching (MPCM)
model, which is an end-to-end system that directly predicts the answer
beginning and ending points in a passage. Our model first adjusts each
word-embedding vector in the passage by multiplying a relevancy weight computed
against the question. Then, we encode the question and weighted passage by
using bi-directional LSTMs. For each point in the passage, our model matches
the context of this point against the encoded question from multiple
perspectives and produces a matching vector. Given those matched vectors, we
employ another bi-directional LSTM to aggregate all the information and predict
the beginning and ending points. Experimental result on the test set of SQuAD
shows that our model achieves a competitive result on the leaderboard.