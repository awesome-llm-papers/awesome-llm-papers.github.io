---
layout: publication
title: Multiplicative LSTM For Sequence Modelling
authors: Ben Krause, Liang Lu, Iain Murray, Steve Renals
conference: Arxiv
year: 2016
bibkey: krause2016multiplicative
citations: 97
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1609.07959'}]
tags: ["Model Architecture"]
short_authors: Krause et al.
---
We introduce multiplicative LSTM (mLSTM), a recurrent neural network
architecture for sequence modelling that combines the long short-term memory
(LSTM) and multiplicative recurrent neural network architectures. mLSTM is
characterised by its ability to have different recurrent transition functions
for each possible input, which we argue makes it more expressive for
autoregressive density estimation. We demonstrate empirically that mLSTM
outperforms standard LSTM and its deep variants for a range of character level
language modelling tasks. In this version of the paper, we regularise mLSTM to
achieve 1.27 bits/char on text8 and 1.24 bits/char on Hutter Prize. We also
apply a purely byte-level mLSTM on the WikiText-2 dataset to achieve a
character level entropy of 1.26 bits/char, corresponding to a word level
perplexity of 88.8, which is comparable to word level LSTMs regularised in
similar ways on the same task.