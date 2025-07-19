---
layout: publication
title: Neural Machine Translation With Byte-level Subwords
authors: Wang Changhan, Cho Kyunghyun, Gu Jiatao
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2019
bibkey: wang2019neural
citations: 111
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.03341'}]
tags: [Reinforcement Learning, AAAI]
---
Almost all existing machine translation models are built on top of
character-based vocabularies: characters, subwords or words. Rare characters
from noisy text or character-rich languages such as Japanese and Chinese
however can unnecessarily take up vocabulary slots and limit its compactness.
Representing text at the level of bytes and using the 256 byte set as
vocabulary is a potential solution to this issue. High computational cost has
however prevented it from being widely deployed or used in practice. In this
paper, we investigate byte-level subwords, specifically byte-level BPE (BBPE),
which is compacter than character vocabulary and has no out-of-vocabulary
tokens, but is more efficient than using pure bytes only is. We claim that
contextualizing BBPE embeddings is necessary, which can be implemented by a
convolutional or recurrent layer. Our experiments show that BBPE has comparable
performance to BPE while its size is only 1/8 of that for BPE. In the
multilingual setting, BBPE maximizes vocabulary sharing across many languages
and achieves better translation quality. Moreover, we show that BBPE enables
transferring models between languages with non-overlapping character sets.