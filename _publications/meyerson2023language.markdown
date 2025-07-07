---
layout: publication
title: 'Language Model Crossover: Variation Through Few-shot Prompting'
authors: Elliot Meyerson et al.
conference: Arxiv
year: 2023
citations: 15
bibkey: meyerson2023language
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2302.12170'}]
tags: [RAG, Few-Shot, In-Context Learning, Prompting]
---
This paper pursues the insight that language models naturally enable an
intelligent variation operator similar in spirit to evolutionary crossover. In
particular, language models of sufficient scale demonstrate in-context
learning, i.e. they can learn from associations between a small number of input
patterns to generate outputs incorporating such associations (also called
few-shot prompting). This ability can be leveraged to form a simple but
powerful variation operator, i.e. to prompt a language model with a few
text-based genotypes (such as code, plain-text sentences, or equations), and to
parse its corresponding output as those genotypes' offspring. The promise of
such language model crossover (which is simple to implement and can leverage
many different open-source language models) is that it enables a simple
mechanism to evolve semantically-rich text representations (with few
domain-specific tweaks), and naturally benefits from current progress in
language models. Experiments in this paper highlight the versatility of
language-model crossover, through evolving binary bit-strings, sentences,
equations, text-to-image prompts, and Python code. The conclusion is that
language model crossover is a promising method for evolving genomes
representable as text.