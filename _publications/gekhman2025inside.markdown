---
layout: publication
title: 'Inside-out: Hidden Factual Knowledge In Llms'
authors: Zorik Gekhman, Eyal Ben David, Hadas Orgad, Eran Ofek, Yonatan Belinkov,
  Idan Szpector, Jonathan Herzig, Roi Reichart
conference: No Venue
year: 2025
bibkey: gekhman2025inside
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67dd5e658dc9e947cee90f81'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2503.15299'}]
tags: ["Tools"]
short_authors: Gekhman et al.
---
This work presents a framework for assessing whether large language models (LLMs) encode more factual knowledge in their parameters than what they express in their outputs. While a few studies hint at this possibility, none has clearly defined or demonstrated this phenomenon. We first propose a formal definition of knowledge, quantifying it for a given question as the fraction of correct-incorrect answer pairs where the correct one is ranked higher. This gives rise to external and internal knowledge, depending on the information used to score individual answer candidates: either the model's observable token-level probabilities or its intermediate computations. Hidden knowledge arises when internal knowledge exceeds external knowledge. We then present a case study, applying this framework to three popular open-weights LLMs in a closed-book QA setup. Our results indicate that: (1) LLMs consistently encode more factual knowledge internally than what they express externally, with an average gap of 40%. (2) Surprisingly, some knowledge is so deeply hidden that a model can internally know an answer perfectly, yet fail to generate it even once, despite large-scale repeated sampling of 1,000 answers. This reveals fundamental limitations in the generation capabilities of LLMs, which (3) puts a practical constraint on scaling test-time compute via repeated answer sampling in closed-book QA: significant performance improvements remain inaccessible because some answers are practically never sampled, yet if they were, we would be guaranteed to rank them first.

https://huggingface.co/discussions/paper/67dd5e658dc9e947cee90f81