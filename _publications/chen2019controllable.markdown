---
layout: publication
title: Controllable Paraphrase Generation With A Syntactic Exemplar
authors: Mingda Chen, Qingming Tang, Sam Wiseman, Kevin Gimpel
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: chen2019controllable
citations: 105
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.00565'}]
tags: ["Training Techniques"]
short_authors: Chen et al.
---
Prior work on controllable text generation usually assumes that the
controlled attribute can take on one of a small set of values known a priori.
In this work, we propose a novel task, where the syntax of a generated sentence
is controlled rather by a sentential exemplar. To evaluate quantitatively with
standard metrics, we create a novel dataset with human annotations. We also
develop a variational model with a neural module specifically designed for
capturing syntactic knowledge and several multitask training objectives to
promote disentangled representation learning. Empirically, the proposed model
is observed to achieve improvements over baselines and learn to capture
desirable characteristics.