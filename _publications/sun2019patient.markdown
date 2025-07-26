---
layout: publication
title: Patient Knowledge Distillation For BERT Model Compression
authors: Siqi Sun, Yu Cheng, Zhe Gan, Jingjing Liu
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: sun2019patient
citations: 553
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.09355'}]
tags: ["EMNLP", "Efficiency", "Model Architecture", "Training Techniques"]
short_authors: Sun et al.
---
Pre-trained language models such as BERT have proven to be highly effective
for natural language processing (NLP) tasks. However, the high demand for
computing resources in training such models hinders their application in
practice. In order to alleviate this resource hunger in large-scale model
training, we propose a Patient Knowledge Distillation approach to compress an
original large model (teacher) into an equally-effective lightweight shallow
network (student). Different from previous knowledge distillation methods,
which only use the output from the last layer of the teacher network for
distillation, our student model patiently learns from multiple intermediate
layers of the teacher model for incremental knowledge extraction, following two
strategies: (\\(i\\)) PKD-Last: learning from the last \\(k\\) layers; and (\\(ii\\))
PKD-Skip: learning from every \\(k\\) layers. These two patient distillation
schemes enable the exploitation of rich information in the teacher's hidden
layers, and encourage the student model to patiently learn from and imitate the
teacher through a multi-layer distillation process. Empirically, this
translates into improved results on multiple NLP tasks with significant gain in
training efficiency, without sacrificing model accuracy.