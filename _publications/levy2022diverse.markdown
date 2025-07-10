---
layout: publication
title: Diverse Demonstrations Improve In-context Compositional Generalization
authors: Itay Levy, Ben Bogin, Jonathan Berant
conference: 'Proceedings of the 61st Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
citations: 20
bibkey: levy2022diverse
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.06800'}]
tags: [RAG, In-Context Learning, Prompting, Training Techniques, Evaluation]
---
In-context learning has shown great success in i.i.d semantic parsing splits,
where the training and test sets are drawn from the same distribution. In this
setup, models are typically prompted with demonstrations that are similar to
the input utterance. However, in the setup of compositional generalization,
where models are tested on outputs with structures that are absent from the
training set, selecting similar demonstrations is insufficient, as often no
example will be similar enough to the input. In this work, we propose a method
to select diverse demonstrations that aims to collectively cover all of the
structures required in the output program, in order to encourage the model to
generalize to new structures from these demonstrations. We empirically show
that combining diverse demonstrations with in-context learning substantially
improves performance across three compositional generalization semantic parsing
datasets in the pure in-context learning setup and when combined with
finetuning.