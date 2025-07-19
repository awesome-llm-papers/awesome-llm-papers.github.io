---
layout: publication
title: Learning To Ask Questions In Open-domain Conversational Systems With Typed
  Decoders
authors: Wang et al.
conference: 'Proceedings of the 56th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2018
bibkey: wang2018learning
citations: 66
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1805.04843'}]
tags: [ACL]
---
Asking good questions in large-scale, open-domain conversational systems is
quite significant yet rather untouched. This task, substantially different from
traditional question generation, requires to question not only with various
patterns but also on diverse and relevant topics. We observe that a good
question is a natural composition of \{\it interrogatives\}, \{\it topic words\},
and \{\it ordinary words\}. Interrogatives lexicalize the pattern of questioning,
topic words address the key information for topic transition in dialogue, and
ordinary words play syntactical and grammatical roles in making a natural
sentence. We devise two typed decoders (\textit\{soft typed decoder\} and
\textit\{hard typed decoder\}) in which a type distribution over the three types
is estimated and used to modulate the final generation distribution. Extensive
experiments show that the typed decoders outperform state-of-the-art baselines
and can generate more meaningful questions.