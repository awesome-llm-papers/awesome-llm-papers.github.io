---
layout: publication
title: 'ERICA: Improving Entity And Relation Understanding For Pre-trained Language
  Models Via Contrastive Learning'
authors: Yujia Qin, Yankai Lin, Ryuichi Takanobu, Zhiyuan Liu, Peng Li, Heng Ji, Minlie
  Huang, Maosong Sun, Jie Zhou
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2021
bibkey: qin2020erica
citations: 83
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.15022'}]
tags: ["Model Architecture", "Tools", "Training Techniques"]
short_authors: Qin et al.
---
Pre-trained Language Models (PLMs) have shown superior performance on various
downstream Natural Language Processing (NLP) tasks. However, conventional
pre-training objectives do not explicitly model relational facts in text, which
are crucial for textual understanding. To address this issue, we propose a
novel contrastive learning framework ERICA to obtain a deep understanding of
the entities and their relations in text. Specifically, we define two novel
pre-training tasks to better understand entities and relations: (1) the entity
discrimination task to distinguish which tail entity can be inferred by the
given head entity and relation; (2) the relation discrimination task to
distinguish whether two relations are close or not semantically, which involves
complex relational reasoning. Experimental results demonstrate that ERICA can
improve typical PLMs (BERT and RoBERTa) on several language understanding
tasks, including relation extraction, entity typing and question answering,
especially under low-resource settings.