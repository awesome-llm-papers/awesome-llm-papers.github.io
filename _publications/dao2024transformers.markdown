---
layout: publication
title: 'Transformers Are Ssms: Generalized Models And Efficient Algorithms Through
  Structured State Space Duality'
authors: Tri Dao, Albert Gu
conference: Arxiv
year: 2024
citations: 15
bibkey: dao2024transformers
additional_links: [{name: Paper, url: 'http://arxiv.org/abs/2405.21060v1'}]
tags: [Transformer, Attention Mechanism, Tools, Language Modeling, Model Architecture]
---
While Transformers have been the main architecture behind deep learning's
success in language modeling, state-space models (SSMs) such as Mamba have
recently been shown to match or outperform Transformers at small to medium
scale. We show that these families of models are actually quite closely
related, and develop a rich framework of theoretical connections between SSMs
and variants of attention, connected through various decompositions of a
well-studied class of structured semiseparable matrices. Our state space
duality (SSD) framework allows us to design a new architecture (Mamba-2) whose
core layer is an a refinement of Mamba's selective SSM that is 2-8X faster,
while continuing to be competitive with Transformers on language modeling.