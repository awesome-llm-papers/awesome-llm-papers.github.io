---
layout: publication
title: Modeling Past And Future For Neural Machine Translation
authors: Zheng et al.
conference: Transactions of the Association for Computational Linguistics
year: 2017
bibkey: zheng2017modeling
citations: 52
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1711.09502'}]
tags: [Model Architecture, TACL, ACL, RAG, Attention Mechanism]
---
Existing neural machine translation systems do not explicitly model what has
been translated and what has not during the decoding phase. To address this
problem, we propose a novel mechanism that separates the source information
into two parts: translated Past contents and untranslated Future contents,
which are modeled by two additional recurrent layers. The Past and Future
contents are fed to both the attention model and the decoder states, which
offers NMT systems the knowledge of translated and untranslated contents.
Experimental results show that the proposed approach significantly improves
translation performance in Chinese-English, German-English and English-German
translation tasks. Specifically, the proposed model outperforms the
conventional coverage model in both of the translation quality and the
alignment error rate.