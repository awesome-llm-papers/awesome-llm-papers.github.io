---
layout: publication
title: 'MWP-BERT: Numeracy-augmented Pre-training For Math Word Problem Solving'
authors: Liang et al.
conference: 'Findings of the Association for Computational Linguistics: NAACL 2022'
year: 2021
bibkey: liang2021mwp
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2107.13435'}]
tags: [Model Architecture, Training Techniques, BERT, Evaluation, ACL, NAACL, Datasets]
---
Math word problem (MWP) solving faces a dilemma in number representation
learning. In order to avoid the number representation issue and reduce the
search space of feasible solutions, existing works striving for MWP solving
usually replace real numbers with symbolic placeholders to focus on logic
reasoning. However, different from common symbolic reasoning tasks like program
synthesis and knowledge graph reasoning, MWP solving has extra requirements in
numerical reasoning. In other words, instead of the number value itself, it is
the reusable numerical property that matters more in numerical reasoning.
Therefore, we argue that injecting numerical properties into symbolic
placeholders with contextualized representation learning schema can provide a
way out of the dilemma in the number representation issue here. In this work,
we introduce this idea to the popular pre-training language model (PLM)
techniques and build MWP-BERT, an effective contextual number representation
PLM. We demonstrate the effectiveness of our MWP-BERT on MWP solving and
several MWP-specific understanding tasks on both English and Chinese
benchmarks.