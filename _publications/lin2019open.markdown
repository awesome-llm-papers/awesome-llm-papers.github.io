---
layout: publication
title: 'Open Sesame: Getting Inside Bert''s Linguistic Knowledge'
authors: Lin Yongjie, Tan Yi Chern, Frank Robert
conference: 'Proceedings of the 2019 ACL Workshop BlackboxNLP: Analyzing and Interpreting
  Neural Networks for NLP'
year: 2019
bibkey: lin2019open
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.01698'}]
tags: [Model Architecture, BERT, ACL, Transformer, Attention Mechanism]
---
How and to what extent does BERT encode syntactically-sensitive hierarchical
information or positionally-sensitive linear information? Recent work has shown
that contextual representations like BERT perform well on tasks that require
sensitivity to linguistic structure. We present here two studies which aim to
provide a better understanding of the nature of BERT's representations. The
first of these focuses on the identification of structurally-defined elements
using diagnostic classifiers, while the second explores BERT's representation
of subject-verb agreement and anaphor-antecedent dependencies through a
quantitative assessment of self-attention vectors. In both cases, we find that
BERT encodes positional information about word tokens well on its lower layers,
but switches to a hierarchically-oriented encoding on higher layers. We
conclude then that BERT's representations do indeed model linguistically
relevant aspects of hierarchical structure, though they do not appear to show
the sharp sensitivity to hierarchical structure that is found in human
processing of reflexive anaphora.