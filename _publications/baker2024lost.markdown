---
layout: publication
title: 'Lost In The Middle, And In-between: Enhancing Language Models'' Ability To
  Reason Over Long Contexts In Multi-hop QA'
authors: Baker et al.
conference: Transactions of the Association for Computational Linguistics
year: 2024
bibkey: baker2024lost
citations: 286
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.10079'}]
tags: [TACL, Ethics And Bias, Prompting, ACL]
---
Previous work finds that recent long-context language models fail to make
equal use of information in the middle of their inputs, preferring pieces of
information located at the tail ends which creates an undue bias in situations
where we would like models to be equally capable of using different parts of
the input. Thus far, the problem has mainly only been considered in settings
with single pieces of critical information, leading us to question what happens
when multiple necessary pieces of information are spread out over the inputs.
Here, we demonstrate the effects of the "lost in the middle" problem in the
multi-hop question answering setting -- in which multiple reasoning "hops" over
disconnected documents are required -- and show that performance degrades not
only with respect to the distance of information from the edges of the context,
but also between pieces of information. Additionally, we experiment with means
of alleviating the problem by reducing superfluous document contents through
knowledge graph triple extraction and summarization, and prompting models to
reason more thoroughly using chain-of-thought prompting.