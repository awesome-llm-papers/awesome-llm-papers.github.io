---
layout: publication
title: 'Udapter: Language Adaptation For Truly Universal Dependency Parsing'
authors: "Ahmet \xDCst\xFCn, Arianna Bisazza, Gosse Bouma, Gertjan van Noord"
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: "\xFCst\xFCn2020udapter"
citations: 100
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.14327'}]
tags: ["EMNLP"]
short_authors: "\xDCst\xFCn et al."
---
Recent advances in multilingual dependency parsing have brought the idea of a
truly universal parser closer to reality. However, cross-language interference
and restrained model capacity remain major obstacles. To address this, we
propose a novel multilingual task adaptation approach based on contextual
parameter generation and adapter modules. This approach enables to learn
adapters via language embeddings while sharing model parameters across
languages. It also allows for an easy but effective integration of existing
linguistic typology features into the parsing network. The resulting parser,
UDapter, outperforms strong monolingual and multilingual baselines on the
majority of both high-resource and low-resource (zero-shot) languages, showing
the success of the proposed adaptation approach. Our in-depth analyses show
that soft parameter sharing via typological features is key to this success.