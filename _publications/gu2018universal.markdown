---
layout: publication
title: Universal Neural Machine Translation For Extremely Low Resource Languages
authors: Jiatao Gu, Hany Hassan, Jacob Devlin, Victor O. K. Li
conference: 'Proceedings of the 2018 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies, Volume 1
  (Long Papers)'
year: 2018
bibkey: gu2018universal
citations: 249
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1802.05368'}]
tags: ["NAACL"]
short_authors: Gu et al.
---
In this paper, we propose a new universal machine translation approach
focusing on languages with a limited amount of parallel data. Our proposed
approach utilizes a transfer-learning approach to share lexical and sentence
level representations across multiple source languages into one target
language. The lexical part is shared through a Universal Lexical Representation
to support multilingual word-level sharing. The sentence-level sharing is
represented by a model of experts from all source languages that share the
source encoders with all other languages. This enables the low-resource
language to utilize the lexical and sentence representations of the higher
resource languages. Our approach is able to achieve 23 BLEU on Romanian-English
WMT2016 using a tiny parallel corpus of 6k sentences, compared to the 18 BLEU
of strong baseline system which uses multilingual training and
back-translation. Furthermore, we show that the proposed approach can achieve
almost 20 BLEU on the same dataset through fine-tuning a pre-trained
multi-lingual system in a zero-shot setting.