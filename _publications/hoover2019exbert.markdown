---
layout: publication
title: 'Exbert: A Visual Analysis Tool To Explore Learned Representations In Transformers
  Models'
authors: Benjamin Hoover, Hendrik Strobelt, Sebastian Gehrmann
conference: 'Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics: System Demonstrations'
year: 2020
bibkey: hoover2019exbert
citations: 141
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1910.05276'}]
tags: ["Model Architecture", "Tools"]
short_authors: Benjamin Hoover, Hendrik Strobelt, Sebastian Gehrmann
---
Large language models can produce powerful contextual representations that
lead to improvements across many NLP tasks. Since these models are typically
guided by a sequence of learned self attention mechanisms and may comprise
undesired inductive biases, it is paramount to be able to explore what the
attention has learned. While static analyses of these models lead to targeted
insights, interactive tools are more dynamic and can help humans better gain an
intuition for the model-internal reasoning process. We present exBERT, an
interactive tool named after the popular BERT language model, that provides
insights into the meaning of the contextual representations by matching a
human-specified input to similar contexts in a large annotated dataset. By
aggregating the annotations of the matching similar contexts, exBERT helps
intuitively explain what each attention-head has learned.