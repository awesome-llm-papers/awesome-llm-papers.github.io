---
layout: publication
title: 'Two Are Better Than One: An Ensemble Of Retrieval- And Generation-based Dialog
  Systems'
authors: Song et al.
conference: Arxiv
year: 2016
bibkey: song2016two
citations: 88
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1610.07149'}]
tags: [Model Architecture, Attention Mechanism]
---
Open-domain human-computer conversation has attracted much attention in the
field of NLP. Contrary to rule- or template-based domain-specific dialog
systems, open-domain conversation usually requires data-driven approaches,
which can be roughly divided into two categories: retrieval-based and
generation-based systems. Retrieval systems search a user-issued utterance
(called a query) in a large database, and return a reply that best matches the
query. Generative approaches, typically based on recurrent neural networks
(RNNs), can synthesize new replies, but they suffer from the problem of
generating short, meaningless utterances. In this paper, we propose a novel
ensemble of retrieval-based and generation-based dialog systems in the open
domain. In our approach, the retrieved candidate, in addition to the original
query, is fed to an RNN-based reply generator, so that the neural model is
aware of more information. The generated reply is then fed back as a new
candidate for post-reranking. Experimental results show that such ensemble
outperforms each single part of it by a large margin.