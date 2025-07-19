---
layout: publication
title: Leveraging Monolingual Data With Self-supervision For Multilingual Neural Machine
  Translation
authors: Siddhant et al.
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: siddhant2020leveraging
citations: 58
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.04816'}]
tags: [ACL, Training Techniques, RAG, Fine Tuning]
---
Over the last few years two promising research directions in low-resource
neural machine translation (NMT) have emerged. The first focuses on utilizing
high-resource languages to improve the quality of low-resource languages via
multilingual NMT. The second direction employs monolingual data with
self-supervision to pre-train translation models, followed by fine-tuning on
small amounts of supervised data. In this work, we join these two lines of
research and demonstrate the efficacy of monolingual data with self-supervision
in multilingual NMT. We offer three major results: (i) Using monolingual data
significantly boosts the translation quality of low-resource languages in
multilingual models. (ii) Self-supervision improves zero-shot translation
quality in multilingual models. (iii) Leveraging monolingual data with
self-supervision provides a viable path towards adding new languages to
multilingual models, getting up to 33 BLEU on ro-en translation without any
parallel data or back-translation.