---
layout: publication
title: 'Multilingual LAMA: Investigating Knowledge In Multilingual Pretrained Language
  Models'
authors: "Nora Kassner, Philipp Dufter, Hinrich Sch\xFCtze"
conference: 'Proceedings of the 16th Conference of the European Chapter of the Association
  for Computational Linguistics: Main Volume'
year: 2021
bibkey: kassner2021multilingual
citations: 73
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2102.00894'}]
tags: ["EACL"]
short_authors: "Nora Kassner, Philipp Dufter, Hinrich Sch\xFCtze"
---
Recently, it has been found that monolingual English language models can be
used as knowledge bases. Instead of structural knowledge base queries, masked
sentences such as "Paris is the capital of [MASK]" are used as probes. We
translate the established benchmarks TREx and GoogleRE into 53 languages.
Working with mBERT, we investigate three questions. (i) Can mBERT be used as a
multilingual knowledge base? Most prior work only considers English. Extending
research to multiple languages is important for diversity and accessibility.
(ii) Is mBERT's performance as knowledge base language-independent or does it
vary from language to language? (iii) A multilingual model is trained on more
text, e.g., mBERT is trained on 104 Wikipedias. Can mBERT leverage this for
better performance? We find that using mBERT as a knowledge base yields varying
performance across languages and pooling predictions across languages improves
performance. Conversely, mBERT exhibits a language bias; e.g., when queried in
Italian, it tends to predict Italy as the country of origin.