---
layout: publication
title: 'KQA Pro: A Dataset With Explicit Compositional Programs For Complex Question
  Answering Over Knowledge Base'
authors: Cao et al.
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2020
bibkey: cao2020kqa
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2007.03875'}]
tags: [Datasets, ACL, Evaluation]
---
Complex question answering over knowledge base (Complex KBQA) is challenging
because it requires various compositional reasoning capabilities, such as
multi-hop inference, attribute comparison, set operation. Existing benchmarks
have some shortcomings that limit the development of Complex KBQA: 1) they only
provide QA pairs without explicit reasoning processes; 2) questions are poor in
diversity or scale. To this end, we introduce KQA Pro, a dataset for Complex
KBQA including ~120K diverse natural language questions. We introduce a
compositional and interpretable programming language KoPL to represent the
reasoning process of complex questions. For each question, we provide the
corresponding KoPL program and SPARQL query, so that KQA Pro serves for both
KBQA and semantic parsing tasks. Experimental results show that SOTA KBQA
methods cannot achieve promising results on KQA Pro as on current datasets,
which suggests that KQA Pro is challenging and Complex KBQA requires further
research efforts. We also treat KQA Pro as a diagnostic dataset for testing
multiple reasoning skills, conduct a thorough evaluation of existing models and
discuss further directions for Complex KBQA. Our codes and datasets can be
obtained from https://github.com/shijx12/KQAPro_Baselines.