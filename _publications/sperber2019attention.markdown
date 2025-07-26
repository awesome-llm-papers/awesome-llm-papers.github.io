---
layout: publication
title: Attention-passing Models For Robust And Data-efficient End-to-end Speech Translation
authors: Matthias Sperber, Graham Neubig, Jan Niehues, Alex Waibel
conference: Transactions of the Association for Computational Linguistics
year: 2019
bibkey: sperber2019attention
citations: 106
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.07209'}]
tags: ["Model Architecture", "TACL", "Training Techniques"]
short_authors: Sperber et al.
---
Speech translation has traditionally been approached through cascaded models
consisting of a speech recognizer trained on a corpus of transcribed speech,
and a machine translation system trained on parallel texts. Several recent
works have shown the feasibility of collapsing the cascade into a single,
direct model that can be trained in an end-to-end fashion on a corpus of
translated speech. However, experiments are inconclusive on whether the cascade
or the direct model is stronger, and have only been conducted under the
unrealistic assumption that both are trained on equal amounts of data, ignoring
other available speech recognition and machine translation corpora.
  In this paper, we demonstrate that direct speech translation models require
more data to perform well than cascaded models, and while they allow including
auxiliary data through multi-task training, they are poor at exploiting such
data, putting them at a severe disadvantage. As a remedy, we propose the use of
end-to-end trainable models with two attention mechanisms, the first
establishing source speech to source text alignments, the second modeling
source to target text alignment. We show that such models naturally decompose
into multi-task-trainable recognition and translation tasks and propose an
attention-passing technique that alleviates error propagation issues in a
previous formulation of a model with two attention stages. Our proposed model
outperforms all examined baselines and is able to exploit auxiliary training
data much more effectively than direct attentional models.