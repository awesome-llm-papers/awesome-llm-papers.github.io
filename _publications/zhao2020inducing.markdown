---
layout: publication
title: Inducing Language-agnostic Multilingual Representations
authors: Wei Zhao, Steffen Eger, Johannes Bjerva, Isabelle Augenstein
conference: 'Proceedings of *SEM 2021: The Tenth Joint Conference on Lexical and Computational
  Semantics'
year: 2020
citations: 15
bibkey: zhao2020inducing
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2008.09112'}]
tags: [Model Architecture, RAG, TACL, ACL, Reinforcement Learning, BERT, Training
    Techniques]
---
Cross-lingual representations have the potential to make NLP techniques
available to the vast majority of languages in the world. However, they
currently require large pretraining corpora or access to typologically similar
languages. In this work, we address these obstacles by removing language
identity signals from multilingual embeddings. We examine three approaches for
this: (i) re-aligning the vector spaces of target languages (all together) to a
pivot source language; (ii) removing language-specific means and variances,
which yields better discriminativeness of embeddings as a by-product; and (iii)
increasing input similarity across languages by removing morphological
contractions and sentence reordering. We evaluate on XNLI and reference-free MT
across 19 typologically diverse languages. Our findings expose the limitations
of these approaches -- unlike vector normalization, vector space re-alignment
and text normalization do not achieve consistent gains across encoders and
languages. Due to the approaches' additive effects, their combination decreases
the cross-lingual transfer gap by 8.9 points (m-BERT) and 18.2 points (XLM-R)
on average across all tasks and languages, however. Our code and models are
publicly available.