---
layout: publication
title: How Multilingual Is Multilingual BERT?
authors: Telmo Pires, Eva Schlinger, Dan Garrette
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: pires2019how
citations: 1050
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.01502'}]
tags: ["Evaluation", "Model Architecture"]
short_authors: Telmo Pires, Eva Schlinger, Dan Garrette
---
In this paper, we show that Multilingual BERT (M-BERT), released by Devlin et
al. (2018) as a single language model pre-trained from monolingual corpora in
104 languages, is surprisingly good at zero-shot cross-lingual model transfer,
in which task-specific annotations in one language are used to fine-tune the
model for evaluation in another language. To understand why, we present a large
number of probing experiments, showing that transfer is possible even to
languages in different scripts, that transfer works best between typologically
similar languages, that monolingual corpora can train models for
code-switching, and that the model can find translation pairs. From these
results, we can conclude that M-BERT does create multilingual representations,
but that these representations exhibit systematic deficiencies affecting
certain language pairs.