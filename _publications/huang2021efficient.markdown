---
layout: publication
title: Efficient Attentions For Long Document Summarization
authors: Luyang Huang, Shuyang Cao, Nikolaus Parulian, Heng Ji, Lu Wang
conference: 'Proceedings of the 2021 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2021
bibkey: huang2021efficient
citations: 108
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.02112'}]
tags: ["NAACL"]
short_authors: Huang et al.
---
The quadratic computational and memory complexities of large Transformers
have limited their scalability for long document summarization. In this paper,
we propose Hepos, a novel efficient encoder-decoder attention with head-wise
positional strides to effectively pinpoint salient information from the source.
We further conduct a systematic study of existing efficient self-attentions.
Combined with Hepos, we are able to process ten times more tokens than existing
models that use full attentions. For evaluation, we present a new dataset,
GovReport, with significantly longer documents and summaries. Results show that
our models produce significantly higher ROUGE scores than competitive
comparisons, including new state-of-the-art results on PubMed. Human evaluation
also shows that our models generate more informative summaries with fewer
unfaithful errors.