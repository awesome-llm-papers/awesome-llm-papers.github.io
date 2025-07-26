---
layout: publication
title: Find Or Classify? Dual Strategy For Slot-value Predictions On Multi-domain
  Dialog State Tracking
authors: Jian-guo Zhang, Kazuma Hashimoto, Chien-sheng Wu, Yao Wan, Philip S. Yu,
  Richard Socher, Caiming Xiong
conference: Arxiv
year: 2019
bibkey: zhang2019find
citations: 104
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1910.03544'}]
tags: ["Datasets", "Model Architecture"]
short_authors: Zhang et al.
---
Dialog state tracking (DST) is a core component in task-oriented dialog
systems. Existing approaches for DST mainly fall into one of two categories,
namely, ontology-based and ontology-free methods. An ontology-based method
selects a value from a candidate-value list for each target slot, while an
ontology-free method extracts spans from dialog contexts. Recent work
introduced a BERT-based model to strike a balance between the two methods by
pre-defining categorical and non-categorical slots. However, it is not clear
enough which slots are better handled by either of the two slot types, and the
way to use the pre-trained model has not been well investigated. In this paper,
we propose a simple yet effective dual-strategy model for DST, by adapting a
single BERT-style reading comprehension model to jointly handle both the
categorical and non-categorical slots. Our experiments on the MultiWOZ datasets
show that our method significantly outperforms the BERT-based counterpart,
finding that the key is a deep interaction between the domain-slot and context
information. When evaluated on noisy (MultiWOZ 2.0) and cleaner (MultiWOZ 2.1)
settings, our method performs competitively and robustly across the two
different settings. Our method sets the new state of the art in the noisy
setting, while performing more robustly than the best model in the cleaner
setting. We also conduct a comprehensive error analysis on the dataset,
including the effects of the dual strategy for each slot, to facilitate future
research.