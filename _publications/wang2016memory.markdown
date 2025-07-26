---
layout: publication
title: Memory-enhanced Decoder For Neural Machine Translation
authors: Mingxuan Wang, Zhengdong Lu, Hang Li, Qun Liu
conference: Proceedings of the 2016 Conference on Empirical Methods in Natural Language
  Processing
year: 2016
bibkey: wang2016memory
citations: 63
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1606.02003'}]
tags: ["EMNLP", "Memory & Context"]
short_authors: Wang et al.
---
We propose to enhance the RNN decoder in a neural machine translator (NMT)
with external memory, as a natural but powerful extension to the state in the
decoding RNN. This memory-enhanced RNN decoder is called \textsc\{MemDec\}. At
each time during decoding, \textsc\{MemDec\} will read from this memory and write
to this memory once, both with content-based addressing. Unlike the unbounded
memory in previous work\cite\{RNNsearch\} to store the representation of source
sentence, the memory in \textsc\{MemDec\} is a matrix with pre-determined size
designed to better capture the information important for the decoding process
at each time step. Our empirical study on Chinese-English translation shows
that it can improve by \\(4.8\\) BLEU upon Groundhog and \\(5.3\\) BLEU upon on Moses,
yielding the best performance achieved with the same training set.