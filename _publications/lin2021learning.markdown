---
layout: publication
title: Learning Language Specific Sub-network For Multilingual Machine Translation
authors: Lin et al.
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2021
bibkey: lin2021learning
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2105.09259'}]
tags: [Model Architecture, ACL, Transformer, RAG, Datasets, SLT]
---
Multilingual neural machine translation aims at learning a single translation
model for multiple languages. These jointly trained models often suffer from
performance degradation on rich-resource language pairs. We attribute this
degeneration to parameter interference. In this paper, we propose LaSS to
jointly train a single unified multilingual MT model. LaSS learns Language
Specific Sub-network (LaSS) for each language pair to counter parameter
interference. Comprehensive experiments on IWSLT and WMT datasets with various
Transformer architectures show that LaSS obtains gains on 36 language pairs by
up to 1.2 BLEU. Besides, LaSS shows its strong generalization performance at
easy extension to new language pairs and zero-shot translation.LaSS boosts
zero-shot translation with an average of 8.3 BLEU on 30 language pairs. Codes
and trained models are available at https://github.com/NLP-Playground/LaSS.