---
layout: publication
title: 'Sentencepiece: A Simple And Language Independent Subword Tokenizer And Detokenizer
  For Neural Text Processing'
authors: Taku Kudo, John Richardson
conference: 'Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing: System Demonstrations'
year: 2018
bibkey: kudo2018sentencepiece
citations: 2639
additional_links: [{name: Code, url: 'https://github.com/google/sentencepiece'}, {
    name: Paper, url: 'https://arxiv.org/abs/1808.06226'}]
tags: ["EMNLP", "Has Code", "Tools"]
short_authors: Taku Kudo, John Richardson
---
This paper describes SentencePiece, a language-independent subword tokenizer
and detokenizer designed for Neural-based text processing, including Neural
Machine Translation. It provides open-source C++ and Python implementations for
subword units. While existing subword segmentation tools assume that the input
is pre-tokenized into word sequences, SentencePiece can train subword models
directly from raw sentences, which allows us to make a purely end-to-end and
language independent system. We perform a validation experiment of NMT on
English-Japanese machine translation, and find that it is possible to achieve
comparable accuracy to direct subword training from raw sentences. We also
compare the performance of subword training and segmentation with various
configurations. SentencePiece is available under the Apache 2 license at
https://github.com/google/sentencepiece.