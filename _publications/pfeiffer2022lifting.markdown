---
layout: publication
title: Lifting The Curse Of Multilinguality By Pre-training Modular Transformers
authors: Pfeiffer et al.
conference: 'Proceedings of the 2022 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2022
bibkey: pfeiffer2022lifting
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2205.06266'}]
tags: [Model Architecture, Training Techniques, ACL, Transformer, NAACL]
---
Multilingual pre-trained models are known to suffer from the curse of
multilinguality, which causes per-language performance to drop as they cover
more languages. We address this issue by introducing language-specific modules,
which allows us to grow the total capacity of the model, while keeping the
total number of trainable parameters per language constant. In contrast with
prior work that learns language-specific components post-hoc, we pre-train the
modules of our Cross-lingual Modular (X-Mod) models from the start. Our
experiments on natural language inference, named entity recognition and
question answering show that our approach not only mitigates the negative
interference between languages, but also enables positive transfer, resulting
in improved monolingual and cross-lingual performance. Furthermore, our
approach enables adding languages post-hoc with no measurable drop in
performance, no longer limiting the model usage to the set of pre-trained
languages.