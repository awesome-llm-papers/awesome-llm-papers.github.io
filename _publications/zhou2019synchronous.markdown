---
layout: publication
title: Synchronous Bidirectional Neural Machine Translation
authors: Long Zhou, Jiajun Zhang, Chengqing Zong
conference: Transactions of the Association for Computational Linguistics
year: 2019
bibkey: zhou2019synchronous
citations: 117
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1905.04847'}]
tags: ["Model Architecture", "TACL"]
short_authors: Long Zhou, Jiajun Zhang, Chengqing Zong
---
Existing approaches to neural machine translation (NMT) generate the target
language sequence token by token from left to right. However, this kind of
unidirectional decoding framework cannot make full use of the target-side
future contexts which can be produced in a right-to-left decoding direction,
and thus suffers from the issue of unbalanced outputs. In this paper, we
introduce a synchronous bidirectional neural machine translation (SB-NMT) that
predicts its outputs using left-to-right and right-to-left decoding
simultaneously and interactively, in order to leverage both of the history and
future information at the same time. Specifically, we first propose a new
algorithm that enables synchronous bidirectional decoding in a single model.
Then, we present an interactive decoding model in which left-to-right
(right-to-left) generation does not only depend on its previously generated
outputs, but also relies on future contexts predicted by right-to-left
(left-to-right) decoding. We extensively evaluate the proposed SB-NMT model on
large-scale NIST Chinese-English, WMT14 English-German, and WMT18
Russian-English translation tasks. Experimental results demonstrate that our
model achieves significant improvements over the strong Transformer model by
3.92, 1.49 and 1.04 BLEU points respectively, and obtains the state-of-the-art
performance on Chinese-English and English-German translation tasks.