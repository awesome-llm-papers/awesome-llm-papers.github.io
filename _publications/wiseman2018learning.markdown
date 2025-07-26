---
layout: publication
title: Learning Neural Templates For Text Generation
authors: Sam Wiseman, Stuart M. Shieber, Alexander M. Rush
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2018
bibkey: wiseman2018learning
citations: 214
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1808.10122'}]
tags: ["EMNLP"]
short_authors: Sam Wiseman, Stuart M. Shieber, Alexander M. Rush
---
While neural, encoder-decoder models have had significant empirical success
in text generation, there remain several unaddressed problems with this style
of generation. Encoder-decoder models are largely (a) uninterpretable, and (b)
difficult to control in terms of their phrasing or content. This work proposes
a neural generation system using a hidden semi-markov model (HSMM) decoder,
which learns latent, discrete templates jointly with learning to generate. We
show that this model learns useful templates, and that these templates make
generation both more interpretable and controllable. Furthermore, we show that
this approach scales to real data sets and achieves strong performance nearing
that of encoder-decoder text generation models.