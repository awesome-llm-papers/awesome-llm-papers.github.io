---
layout: publication
title: Automatic Detection Of Generated Text Is Easiest When Humans Are Fooled
authors: Daphne Ippolito, Daniel Duckworth, Chris Callison-burch, Douglas Eck
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: ippolito2019automatic
citations: 180
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.00650'}]
tags: ["Datasets"]
short_authors: Ippolito et al.
---
Recent advancements in neural language modelling make it possible to rapidly
generate vast amounts of human-sounding text. The capabilities of humans and
automatic discriminators to detect machine-generated text have been a large
source of research interest, but humans and machines rely on different cues to
make their decisions. Here, we perform careful benchmarking and analysis of
three popular sampling-based decoding strategies---top-\\(k\\), nucleus sampling,
and untruncated random sampling---and show that improvements in decoding
methods have primarily optimized for fooling humans. This comes at the expense
of introducing statistical abnormalities that make detection easy for automatic
systems. We also show that though both human and automatic detector performance
improve with longer excerpt length, even multi-sentence excerpts can fool
expert human raters over 30% of the time. Our findings reveal the importance of
using both human and automatic detectors to assess the humanness of text
generation systems.