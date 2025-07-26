---
layout: publication
title: 'Compositional Generalization In Semantic Parsing: Pre-training Vs. Specialized
  Architectures'
authors: "Daniel Furrer, Marc van Zee, Nathan Scales, Nathanael Sch\xE4rli"
conference: Arxiv
year: 2020
bibkey: furrer2020compositional
citations: 81
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2007.08970'}]
tags: ["Datasets", "Training Techniques"]
short_authors: Furrer et al.
---
While mainstream machine learning methods are known to have limited ability
to compositionally generalize, new architectures and techniques continue to be
proposed to address this limitation. We investigate state-of-the-art techniques
and architectures in order to assess their effectiveness in improving
compositional generalization in semantic parsing tasks based on the SCAN and
CFQ datasets. We show that masked language model (MLM) pre-training rivals
SCAN-inspired architectures on primitive holdout splits. On a more complex
compositional task, we show that pre-training leads to significant improvements
in performance vs. comparable non-pre-trained models, whereas architectures
proposed to encourage compositional generalization on SCAN or in the area of
algorithm learning fail to lead to significant improvements. We establish a new
state of the art on the CFQ compositional generalization benchmark using MLM
pre-training together with an intermediate representation.