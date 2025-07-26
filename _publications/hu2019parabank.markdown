---
layout: publication
title: 'Parabank: Monolingual Bitext Generation And Sentential Paraphrasing Via Lexically-constrained
  Neural Machine Translation'
authors: J. Edward Hu, Rachel Rudinger, Matt Post, Benjamin van Durme
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2019
bibkey: hu2019parabank
citations: 85
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1901.03644'}]
tags: ["AAAI", "Datasets"]
short_authors: Hu et al.
---
We present ParaBank, a large-scale English paraphrase dataset that surpasses
prior work in both quantity and quality. Following the approach of ParaNMT, we
train a Czech-English neural machine translation (NMT) system to generate novel
paraphrases of English reference sentences. By adding lexical constraints to
the NMT decoding procedure, however, we are able to produce multiple
high-quality sentential paraphrases per source sentence, yielding an English
paraphrase resource with more than 4 billion generated tokens and exhibiting
greater lexical diversity. Using human judgments, we also demonstrate that
ParaBank's paraphrases improve over ParaNMT on both semantic similarity and
fluency. Finally, we use ParaBank to train a monolingual NMT model with the
same support for lexically-constrained decoding for sentence rewriting tasks.