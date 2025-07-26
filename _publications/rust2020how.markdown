---
layout: publication
title: How Good Is Your Tokenizer? On The Monolingual Performance Of Multilingual
  Language Models
authors: "Phillip Rust, Jonas Pfeiffer, Ivan Vuli\u0107, Sebastian Ruder, Iryna Gurevych"
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2021
bibkey: rust2020how
citations: 139
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.15613'}]
tags: ["Evaluation Frameworks", "Evaluation"]
short_authors: Rust et al.
---
In this work, we provide a systematic and comprehensive empirical comparison
of pretrained multilingual language models versus their monolingual
counterparts with regard to their monolingual task performance. We study a set
of nine typologically diverse languages with readily available pretrained
monolingual models on a set of five diverse monolingual downstream tasks. We
first aim to establish, via fair and controlled comparisons, if a gap between
the multilingual and the corresponding monolingual representation of that
language exists, and subsequently investigate the reason for any performance
difference. To disentangle conflating factors, we train new monolingual models
on the same data, with monolingually and multilingually trained tokenizers. We
find that while the pretraining data size is an important factor, a designated
monolingual tokenizer plays an equally important role in the downstream
performance. Our results show that languages that are adequately represented in
the multilingual model's vocabulary exhibit negligible performance decreases
over their monolingual counterparts. We further find that replacing the
original multilingual tokenizer with the specialized monolingual tokenizer
improves the downstream performance of the multilingual model for almost every
task and language.