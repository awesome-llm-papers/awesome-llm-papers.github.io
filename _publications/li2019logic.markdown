---
layout: publication
title: A Logic-driven Framework For Consistency Of Neural Models
authors: Li et al.
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: li2019logic
citations: 63
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.00126'}]
tags: [RAG, Tools, EMNLP, Training Techniques]
---
While neural models show remarkable accuracy on individual predictions, their
internal beliefs can be inconsistent across examples. In this paper, we
formalize such inconsistency as a generalization of prediction error. We
propose a learning framework for constraining models using logic rules to
regularize them away from inconsistency. Our framework can leverage both
labeled and unlabeled examples and is directly compatible with off-the-shelf
learning schemes without model redesign. We instantiate our framework on
natural language inference, where experiments show that enforcing invariants
stated in logic can help make the predictions of neural models both accurate
and consistent.