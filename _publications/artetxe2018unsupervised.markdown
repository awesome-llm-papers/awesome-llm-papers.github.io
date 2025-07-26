---
layout: publication
title: Unsupervised Statistical Machine Translation
authors: Mikel Artetxe, Gorka Labaka, Eneko Agirre
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2018
bibkey: artetxe2018unsupervised
citations: 324
additional_links: [{name: Code, url: 'https://github.com/artetxem/monoses'}, {name: Paper,
    url: 'https://arxiv.org/abs/1809.01272'}]
tags: ["EMNLP"]
short_authors: Mikel Artetxe, Gorka Labaka, Eneko Agirre
---
While modern machine translation has relied on large parallel corpora, a
recent line of work has managed to train Neural Machine Translation (NMT)
systems from monolingual corpora only (Artetxe et al., 2018c; Lample et al.,
2018). Despite the potential of this approach for low-resource settings,
existing systems are far behind their supervised counterparts, limiting their
practical interest. In this paper, we propose an alternative approach based on
phrase-based Statistical Machine Translation (SMT) that significantly closes
the gap with supervised systems. Our method profits from the modular
architecture of SMT: we first induce a phrase table from monolingual corpora
through cross-lingual embedding mappings, combine it with an n-gram language
model, and fine-tune hyperparameters through an unsupervised MERT variant. In
addition, iterative backtranslation improves results further, yielding, for
instance, 14.08 and 26.22 BLEU points in WMT 2014 English-German and
English-French, respectively, an improvement of more than 7-10 BLEU points over
previous unsupervised systems, and closing the gap with supervised SMT (Moses
trained on Europarl) down to 2-5 BLEU points. Our implementation is available
at https://github.com/artetxem/monoses