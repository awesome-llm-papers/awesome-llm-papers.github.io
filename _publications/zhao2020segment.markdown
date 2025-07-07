---
layout: publication
title: 'SEAL: Segment-wise Extractive-abstractive Long-form Text Summarization'
authors: Yao Zhao, Mohammad Saleh, Peter J. Liu
conference: Arxiv
year: 2020
citations: 17
bibkey: zhao2020segment
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2006.10213'}]
tags: [Transformer, Attention Mechanism, Interpretability and Explainability, Model
    Architecture]
---
Most prior work in the sequence-to-sequence paradigm focused on datasets with
input sequence lengths in the hundreds of tokens due to the computational
constraints of common RNN and Transformer architectures. In this paper, we
study long-form abstractive text summarization, a sequence-to-sequence setting
with input sequence lengths up to 100,000 tokens and output sequence lengths up
to 768 tokens. We propose SEAL, a Transformer-based model, featuring a new
encoder-decoder attention that dynamically extracts/selects input snippets to
sparsely attend to for each output segment. Using only the original documents
and summaries, we derive proxy labels that provide weak supervision for
extractive layers simultaneously with regular supervision from abstractive
summaries. The SEAL model achieves state-of-the-art results on existing
long-form summarization tasks, and outperforms strong baseline models on a new
dataset/task we introduce, Search2Wiki, with much longer input text. Since
content selection is explicit in the SEAL model, a desirable side effect is
that the selection can be inspected for enhanced interpretability.