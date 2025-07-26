---
layout: publication
title: 'TLDR: Extreme Summarization Of Scientific Documents'
authors: Isabel Cachola, Kyle Lo, Arman Cohan, Daniel S. Weld
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2020'
year: 2020
bibkey: cachola2020tldr
citations: 146
additional_links: [{name: Code, url: 'https://github.com/allenai/scitldr'}, {name: Paper,
    url: 'https://arxiv.org/abs/2004.15011'}]
tags: ["EMNLP"]
short_authors: Cachola et al.
---
We introduce TLDR generation, a new form of extreme summarization, for
scientific papers. TLDR generation involves high source compression and
requires expert background knowledge and understanding of complex
domain-specific language. To facilitate study on this task, we introduce
SciTLDR, a new multi-target dataset of 5.4K TLDRs over 3.2K papers. SciTLDR
contains both author-written and expert-derived TLDRs, where the latter are
collected using a novel annotation protocol that produces high-quality
summaries while minimizing annotation burden. We propose CATTS, a simple yet
effective learning strategy for generating TLDRs that exploits titles as an
auxiliary training signal. CATTS improves upon strong baselines under both
automated metrics and human evaluations. Data and code are publicly available
at https://github.com/allenai/scitldr.