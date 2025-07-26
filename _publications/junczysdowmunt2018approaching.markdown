---
layout: publication
title: Approaching Neural Grammatical Error Correction As A Low-resource Machine Translation
  Task
authors: Marcin Junczys-dowmunt, Roman Grundkiewicz, Shubha Guha, Kenneth Heafield
conference: 'Proceedings of the 2018 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies, Volume 1
  (Long Papers)'
year: 2018
bibkey: junczysdowmunt2018approaching
citations: 178
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1804.05940'}]
tags: ["NAACL"]
short_authors: Junczys-dowmunt et al.
---
Previously, neural methods in grammatical error correction (GEC) did not
reach state-of-the-art results compared to phrase-based statistical machine
translation (SMT) baselines. We demonstrate parallels between neural GEC and
low-resource neural MT and successfully adapt several methods from low-resource
MT to neural GEC. We further establish guidelines for trustable results in
neural GEC and propose a set of model-independent methods for neural GEC that
can be easily applied in most GEC settings. Proposed methods include adding
source-side noise, domain-adaptation techniques, a GEC-specific
training-objective, transfer learning with monolingual data, and ensembling of
independently trained GEC models and language models. The combined effects of
these methods result in better than state-of-the-art neural GEC models that
outperform previously best neural GEC systems by more than 10% M\\(^2\\) on the
CoNLL-2014 benchmark and 5.9% on the JFLEG test set. Non-neural
state-of-the-art systems are outperformed by more than 2% on the CoNLL-2014
benchmark and by 4% on JFLEG.