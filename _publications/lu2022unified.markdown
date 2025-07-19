---
layout: publication
title: Unified Structure Generation For Universal Information Extraction
authors: Lu et al.
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
bibkey: lu2022unified
citations: 265
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.12277'}]
tags: [Prompting, Tools, ACL, Few Shot, Datasets]
---
Information extraction suffers from its varying targets, heterogeneous
structures, and demand-specific schemas. In this paper, we propose a unified
text-to-structure generation framework, namely UIE, which can universally model
different IE tasks, adaptively generate targeted structures, and
collaboratively learn general IE abilities from different knowledge sources.
Specifically, UIE uniformly encodes different extraction structures via a
structured extraction language, adaptively generates target extractions via a
schema-based prompt mechanism - structural schema instructor, and captures the
common IE abilities via a large-scale pre-trained text-to-structure model.
Experiments show that UIE achieved the state-of-the-art performance on 4 IE
tasks, 13 datasets, and on all supervised, low-resource, and few-shot settings
for a wide range of entity, relation, event and sentiment extraction tasks and
their unification. These results verified the effectiveness, universality, and
transferability of UIE.