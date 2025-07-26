---
layout: publication
title: Grounded Adaptation For Zero-shot Executable Semantic Parsing
authors: Victor Zhong, Mike Lewis, Sida I. Wang, Luke Zettlemoyer
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: zhong2020grounded
citations: 79
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2009.07396'}]
tags: ["EMNLP", "Training Techniques"]
short_authors: Zhong et al.
---
We propose Grounded Adaptation for Zero-shot Executable Semantic Parsing
(GAZP) to adapt an existing semantic parser to new environments (e.g. new
database schemas). GAZP combines a forward semantic parser with a backward
utterance generator to synthesize data (e.g. utterances and SQL queries) in the
new environment, then selects cycle-consistent examples to adapt the parser.
Unlike data-augmentation, which typically synthesizes unverified examples in
the training environment, GAZP synthesizes examples in the new environment
whose input-output consistency are verified. On the Spider, Sparc, and CoSQL
zero-shot semantic parsing tasks, GAZP improves logical form and execution
accuracy of the baseline parser. Our analyses show that GAZP outperforms
data-augmentation in the training environment, performance increases with the
amount of GAZP-synthesized data, and cycle-consistency is central to successful
adaptation.