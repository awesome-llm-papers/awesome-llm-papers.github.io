---
layout: publication
title: Towards Zero-shot Frame Semantic Parsing For Domain Scaling
authors: Ankur Bapna, Gokhan Tur, Dilek Hakkani-tur, Larry Heck
conference: Interspeech 2017
year: 2017
bibkey: bapna2017towards
citations: 134
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1707.02363'}]
tags: ["INTERSPEECH"]
short_authors: Bapna et al.
---
State-of-the-art slot filling models for goal-oriented human/machine
conversational language understanding systems rely on deep learning methods.
While multi-task training of such models alleviates the need for large
in-domain annotated datasets, bootstrapping a semantic parsing model for a new
domain using only the semantic frame, such as the back-end API or knowledge
graph schema, is still one of the holy grail tasks of language understanding
for dialogue systems. This paper proposes a deep learning based approach that
can utilize only the slot description in context without the need for any
labeled or unlabeled in-domain examples, to quickly bootstrap a new domain. The
main idea of this paper is to leverage the encoding of the slot names and
descriptions within a multi-task deep learned slot filling model, to implicitly
align slots across domains. The proposed approach is promising for solving the
domain scaling problem and eliminating the need for any manually annotated data
or explicit schema alignment. Furthermore, our experiments on multiple domains
show that this approach results in significantly better slot-filling
performance when compared to using only in-domain data, especially in the low
data regime.