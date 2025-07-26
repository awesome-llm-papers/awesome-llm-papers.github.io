---
layout: publication
title: Investigating Entity Knowledge In BERT With Simple Neural End-to-end Entity
  Linking
authors: Samuel Broscheit
conference: Proceedings of the 23rd Conference on Computational Natural Language Learning
  (CoNLL)
year: 2019
bibkey: broscheit2019investigating
citations: 64
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2003.05473'}]
tags: ["Evaluation", "Model Architecture", "Training Techniques"]
short_authors: Samuel Broscheit
---
A typical architecture for end-to-end entity linking systems consists of
three steps: mention detection, candidate generation and entity disambiguation.
In this study we investigate the following questions: (a) Can all those steps
be learned jointly with a model for contextualized text-representations, i.e.
BERT (Devlin et al., 2019)? (b) How much entity knowledge is already contained
in pretrained BERT? (c) Does additional entity knowledge improve BERT's
performance in downstream tasks? To this end, we propose an extreme
simplification of the entity linking setup that works surprisingly well: simply
cast it as a per token classification over the entire entity vocabulary (over
700K classes in our case). We show on an entity linking benchmark that (i) this
model improves the entity representations over plain BERT, (ii) that it
outperforms entity linking architectures that optimize the tasks separately and
(iii) that it only comes second to the current state-of-the-art that does
mention detection and entity disambiguation jointly. Additionally, we
investigate the usefulness of entity-aware token-representations in the
text-understanding benchmark GLUE, as well as the question answering benchmarks
SQUAD V2 and SWAG and also the EN-DE WMT14 machine translation benchmark. To
our surprise, we find that most of those benchmarks do not benefit from
additional entity knowledge, except for a task with very small training data,
the RTE task in GLUE, which improves by 2%.