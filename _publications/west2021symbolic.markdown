---
layout: publication
title: 'Symbolic Knowledge Distillation: From General Language Models To Commonsense
  Models'
authors: Peter West, Chandra Bhagavatula, Jack Hessel, Jena D. Hwang, Liwei Jiang,
  Ronan Le Bras, Ximing Lu, Sean Welleck, Yejin Choi
conference: 'Proceedings of the 2022 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2022
bibkey: west2021symbolic
citations: 129
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2110.07178'}]
tags: ["NAACL"]
short_authors: West et al.
---
The common practice for training commonsense models has gone
from-human-to-corpus-to-machine: humans author commonsense knowledge graphs in
order to train commonsense models. In this work, we investigate an alternative,
from-machine-to-corpus-to-machine: general language models author these
commonsense knowledge graphs to train commonsense models. Our study leads to a
new framework, Symbolic Knowledge Distillation. As with prior art in Knowledge
Distillation (Hinton et al., 2015), our approach uses larger models to teach
smaller models. A key difference is that we distill knowledge symbolically-as
text-in addition to the neural model. We also distill only one aspect-the
commonsense of a general language model teacher, allowing the student to be a
different type, a commonsense model. Altogether, we show that careful prompt
engineering and a separately trained critic model allow us to selectively
distill high-quality causal commonsense from GPT-3, a general language model.
Empirical results demonstrate that, for the first time, a human-authored
commonsense knowledge graph is surpassed by our automatically distilled variant
in all three criteria: quantity, quality, and diversity. In addition, it
results in a neural commonsense model that surpasses the teacher model's
commonsense capabilities despite its 100x smaller size. We apply this to the
ATOMIC resource, and share our new symbolic knowledge graph and commonsense
models.