---
layout: publication
title: 'Poly-encoders: Transformer Architectures And Pre-training Strategies For Fast
  And Accurate Multi-sentence Scoring'
authors: Samuel Humeau, Kurt Shuster, Marie-anne Lachaux, Jason Weston
conference: Arxiv
year: 2019
bibkey: humeau2019poly
citations: 172
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1905.01969'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Humeau et al.
---
The use of deep pre-trained bidirectional transformers has led to remarkable
progress in a number of applications (Devlin et al., 2018). For tasks that make
pairwise comparisons between sequences, matching a given input with a
corresponding label, two approaches are common: Cross-encoders performing full
self-attention over the pair and Bi-encoders encoding the pair separately. The
former often performs better, but is too slow for practical use. In this work,
we develop a new transformer architecture, the Poly-encoder, that learns global
rather than token level self-attention features. We perform a detailed
comparison of all three approaches, including what pre-training and fine-tuning
strategies work best. We show our models achieve state-of-the-art results on
three existing tasks; that Poly-encoders are faster than Cross-encoders and
more accurate than Bi-encoders; and that the best results are obtained by
pre-training on large datasets similar to the downstream tasks.