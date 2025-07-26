---
layout: publication
title: Character-level Language Modeling With Deeper Self-attention
authors: Rami Al-rfou, Dokook Choe, Noah Constant, Mandy Guo, Llion Jones
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2019
bibkey: alrfou2018character
citations: 298
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1808.04444'}]
tags: ["AAAI", "Model Architecture"]
short_authors: Al-rfou et al.
---
LSTMs and other RNN variants have shown strong performance on character-level
language modeling. These models are typically trained using truncated
backpropagation through time, and it is common to assume that their success
stems from their ability to remember long-term contexts. In this paper, we show
that a deep (64-layer) transformer model with fixed context outperforms RNN
variants by a large margin, achieving state of the art on two popular
benchmarks: 1.13 bits per character on text8 and 1.06 on enwik8. To get good
results at this depth, we show that it is important to add auxiliary losses,
both at intermediate network layers and intermediate sequence positions.