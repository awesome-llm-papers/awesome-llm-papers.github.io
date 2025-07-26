---
layout: publication
title: Guided Alignment Training For Topic-aware Neural Machine Translation
authors: Wenhu Chen, Evgeny Matusov, Shahram Khadivi, Jan-thorsten Peter
conference: Arxiv
year: 2016
bibkey: chen2016guided
citations: 85
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1607.01628'}]
tags: ["Training Techniques"]
short_authors: Chen et al.
---
In this paper, we propose an effective way for biasing the attention
mechanism of a sequence-to-sequence neural machine translation (NMT) model
towards the well-studied statistical word alignment models. We show that our
novel guided alignment training approach improves translation quality on
real-life e-commerce texts consisting of product titles and descriptions,
overcoming the problems posed by many unknown words and a large type/token
ratio. We also show that meta-data associated with input texts such as topic or
category information can significantly improve translation quality when used as
an additional signal to the decoder part of the network. With both novel
features, the BLEU score of the NMT system on a product title set improves from
18.6 to 21.3%. Even larger MT quality gains are obtained through domain
adaptation of a general domain NMT system to e-commerce data. The developed NMT
system also performs well on the IWSLT speech translation task, where an
ensemble of four variant systems outperforms the phrase-based baseline by 2.1%
BLEU absolute.