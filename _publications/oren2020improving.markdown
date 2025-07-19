---
layout: publication
title: Improving Compositional Generalization In Semantic Parsing
authors: Oren et al.
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2020'
year: 2020
bibkey: oren2020improving
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.05647'}]
tags: [Model Architecture, Training Techniques, BERT, ACL, EMNLP, Attention Mechanism]
---
Generalization of models to out-of-distribution (OOD) data has captured
tremendous attention recently. Specifically, compositional generalization,
i.e., whether a model generalizes to new structures built of components
observed during training, has sparked substantial interest. In this work, we
investigate compositional generalization in semantic parsing, a natural
test-bed for compositional generalization, as output programs are constructed
from sub-components. We analyze a wide variety of models and propose multiple
extensions to the attention module of the semantic parser, aiming to improve
compositional generalization. We find that the following factors improve
compositional generalization: (a) using contextual representations, such as
ELMo and BERT, (b) informing the decoder what input tokens have previously been
attended to, (c) training the decoder attention to agree with pre-computed
token alignments, and (d) downsampling examples corresponding to frequent
program templates. While we substantially reduce the gap between
in-distribution and OOD generalization, performance on OOD compositions is
still substantially lower.