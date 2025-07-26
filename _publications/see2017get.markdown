---
layout: publication
title: 'Get To The Point: Summarization With Pointer-generator Networks'
authors: Abigail See, Peter J. Liu, Christopher D. Manning
conference: 'Proceedings of the 55th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2017
bibkey: see2017get
citations: 3783
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1704.04368'}]
tags: ["Model Architecture"]
short_authors: Abigail See, Peter J. Liu, Christopher D. Manning
---
Neural sequence-to-sequence models have provided a viable new approach for
abstractive text summarization (meaning they are not restricted to simply
selecting and rearranging passages from the original text). However, these
models have two shortcomings: they are liable to reproduce factual details
inaccurately, and they tend to repeat themselves. In this work we propose a
novel architecture that augments the standard sequence-to-sequence attentional
model in two orthogonal ways. First, we use a hybrid pointer-generator network
that can copy words from the source text via pointing, which aids accurate
reproduction of information, while retaining the ability to produce novel words
through the generator. Second, we use coverage to keep track of what has been
summarized, which discourages repetition. We apply our model to the CNN / Daily
Mail summarization task, outperforming the current abstractive state-of-the-art
by at least 2 ROUGE points.