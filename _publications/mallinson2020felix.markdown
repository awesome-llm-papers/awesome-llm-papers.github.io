---
layout: publication
title: 'Felix: Flexible Text Editing Through Tagging And Insertion'
authors: Mallinson et al.
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2020'
year: 2020
bibkey: mallinson2020felix
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2003.10687'}]
tags: [Masked Language Model, Merging, Training Techniques, BERT, ACL, EMNLP, GPT]
---
We present Felix --- a flexible text-editing approach for generation,
designed to derive the maximum benefit from the ideas of decoding with
bi-directional contexts and self-supervised pre-training. In contrast to
conventional sequence-to-sequence (seq2seq) models, Felix is efficient in
low-resource settings and fast at inference time, while being capable of
modeling flexible input-output transformations. We achieve this by decomposing
the text-editing task into two sub-tasks: tagging to decide on the subset of
input tokens and their order in the output text and insertion to in-fill the
missing tokens in the output not present in the input. The tagging model
employs a novel Pointer mechanism, while the insertion model is based on a
Masked Language Model. Both of these models are chosen to be non-autoregressive
to guarantee faster inference. Felix performs favourably when compared to
recent text-editing methods and strong seq2seq baselines when evaluated on four
NLG tasks: Sentence Fusion, Machine Translation Automatic Post-Editing,
Summarization, and Text Simplification.