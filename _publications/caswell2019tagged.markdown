---
layout: publication
title: Tagged Back-translation
authors: Isaac Caswell, Ciprian Chelba, David Grangier
conference: 'Proceedings of the Fourth Conference on Machine Translation (Volume 1:
  Research Papers)'
year: 2019
bibkey: caswell2019tagged
citations: 188
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.06442'}]
tags: []
short_authors: Isaac Caswell, Ciprian Chelba, David Grangier
---
Recent work in Neural Machine Translation (NMT) has shown significant quality
gains from noised-beam decoding during back-translation, a method to generate
synthetic parallel data. We show that the main role of such synthetic noise is
not to diversify the source side, as previously suggested, but simply to
indicate to the model that the given source is synthetic. We propose a simpler
alternative to noising techniques, consisting of tagging back-translated source
sentences with an extra token. Our results on WMT outperform noised
back-translation in English-Romanian and match performance on English-German,
re-defining state-of-the-art in the former.