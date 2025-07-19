---
layout: publication
title: 'Jump To Better Conclusions: SCAN Both Left And Right'
authors: Bastings et al.
conference: 'Proceedings of the 2018 EMNLP Workshop BlackboxNLP: Analyzing and Interpreting
  Neural Networks for NLP'
year: 2018
bibkey: bastings2018jump
citations: 58
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1809.04640'}]
tags: [EMNLP, Datasets]
---
Lake and Baroni (2018) recently introduced the SCAN data set, which consists
of simple commands paired with action sequences and is intended to test the
strong generalization abilities of recurrent sequence-to-sequence models. Their
initial experiments suggested that such models may fail because they lack the
ability to extract systematic rules. Here, we take a closer look at SCAN and
show that it does not always capture the kind of generalization that it was
designed for. To mitigate this we propose a complementary dataset, which
requires mapping actions back to the original commands, called NACS. We show
that models that do well on SCAN do not necessarily do well on NACS, and that
NACS exhibits properties more closely aligned with realistic use-cases for
sequence-to-sequence models.