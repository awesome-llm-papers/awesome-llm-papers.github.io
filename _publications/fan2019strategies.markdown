---
layout: publication
title: Strategies For Structuring Story Generation
authors: Angela Fan, Mike Lewis, Yann Dauphin
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: fan2019strategies
citations: 193
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1902.01109'}]
tags: []
short_authors: Angela Fan, Mike Lewis, Yann Dauphin
---
Writers generally rely on plans or sketches to write long stories, but most
current language models generate word by word from left to right. We explore
coarse-to-fine models for creating narrative texts of several hundred words,
and introduce new models which decompose stories by abstracting over actions
and entities. The model first generates the predicate-argument structure of the
text, where different mentions of the same entity are marked with placeholder
tokens. It then generates a surface realization of the predicate-argument
structure, and finally replaces the entity placeholders with context-sensitive
names and references. Human judges prefer the stories from our models to a wide
range of previous approaches to hierarchical text generation. Extensive
analysis shows that our methods can help improve the diversity and coherence of
events and entities in generated stories.