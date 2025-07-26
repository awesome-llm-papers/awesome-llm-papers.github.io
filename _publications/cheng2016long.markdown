---
layout: publication
title: Long Short-term Memory-networks For Machine Reading
authors: Jianpeng Cheng, Li Dong, Mirella Lapata
conference: Proceedings of the 2016 Conference on Empirical Methods in Natural Language
  Processing
year: 2016
bibkey: cheng2016long
citations: 1036
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1601.06733'}]
tags: ["EMNLP", "Model Architecture"]
short_authors: Jianpeng Cheng, Li Dong, Mirella Lapata
---
In this paper we address the question of how to render sequence-level
networks better at handling structured input. We propose a machine reading
simulator which processes text incrementally from left to right and performs
shallow reasoning with memory and attention. The reader extends the Long
Short-Term Memory architecture with a memory network in place of a single
memory cell. This enables adaptive memory usage during recurrence with neural
attention, offering a way to weakly induce relations among tokens. The system
is initially designed to process a single sequence but we also demonstrate how
to integrate it with an encoder-decoder architecture. Experiments on language
modeling, sentiment analysis, and natural language inference show that our
model matches or outperforms the state of the art.