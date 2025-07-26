---
layout: publication
title: 'Mintl: Minimalist Transfer Learning For Task-oriented Dialogue Systems'
authors: Zhaojiang Lin, Andrea Madotto, Genta Indra Winata, Pascale Fung
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: lin2020mintl
citations: 141
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2009.12005'}]
tags: ["Efficiency", "Fine-Tuning", "Tools", "Training Techniques"]
short_authors: Lin et al.
---
In this paper, we propose Minimalist Transfer Learning (MinTL) to simplify
the system design process of task-oriented dialogue systems and alleviate the
over-dependency on annotated data. MinTL is a simple yet effective transfer
learning framework, which allows us to plug-and-play pre-trained seq2seq
models, and jointly learn dialogue state tracking and dialogue response
generation. Unlike previous approaches, which use a copy mechanism to
"carryover" the old dialogue states to the new one, we introduce Levenshtein
belief spans (Lev), that allows efficient dialogue state tracking with a
minimal generation length. We instantiate our learning framework with two
pre-trained backbones: T5 and BART, and evaluate them on MultiWOZ. Extensive
experiments demonstrate that: 1) our systems establish new state-of-the-art
results on end-to-end response generation, 2) MinTL-based systems are more
robust than baseline methods in the low resource setting, and they achieve
competitive results with only 20% training data, and 3) Lev greatly improves
the inference efficiency.