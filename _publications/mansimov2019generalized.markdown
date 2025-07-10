---
layout: publication
title: A Generalized Framework Of Sequence Generation With Application To Undirected
  Sequence Models
authors: Elman Mansimov, Alex Wang, Sean Welleck, Kyunghyun Cho
conference: Arxiv
year: 2019
citations: 49
bibkey: mansimov2019generalized
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1905.12790'}]
tags: [Language Modeling, Model Architecture, Attention Mechanism, GPT, WMT, Tools,
  BERT]
---
Undirected neural sequence models such as BERT (Devlin et al., 2019) have
received renewed interest due to their success on discriminative natural
language understanding tasks such as question-answering and natural language
inference. The problem of generating sequences directly from these models has
received relatively little attention, in part because generating from
undirected models departs significantly from conventional monotonic generation
in directed sequence models. We investigate this problem by proposing a
generalized model of sequence generation that unifies decoding in directed and
undirected models. The proposed framework models the process of generation
rather than the resulting sequence, and under this framework, we derive various
neural sequence models as special cases, such as autoregressive,
semi-autoregressive, and refinement-based non-autoregressive models. This
unification enables us to adapt decoding algorithms originally developed for
directed sequence models to undirected sequence models. We demonstrate this by
evaluating various handcrafted and learned decoding strategies on a BERT-like
machine translation model (Lample & Conneau, 2019). The proposed approach
achieves constant-time translation results on par with linear-time translation
results from the same undirected sequence model, while both are competitive
with the state-of-the-art on WMT'14 English-German translation.