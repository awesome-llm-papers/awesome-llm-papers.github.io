---
layout: publication
title: What Do You Learn From Context? Probing For Sentence Structure In Contextualized
  Word Representations
authors: Ian Tenney, Patrick Xia, Berlin Chen, Alex Wang, Adam Poliak, R Thomas Mccoy,
  Najoung Kim, Benjamin van Durme, Samuel R. Bowman, Dipanjan Das, Ellie Pavlick
conference: Arxiv
year: 2019
bibkey: tenney2019what
citations: 439
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1905.06316'}]
tags: ["Model Architecture"]
short_authors: Tenney et al.
---
Contextualized representation models such as ELMo (Peters et al., 2018a) and
BERT (Devlin et al., 2018) have recently achieved state-of-the-art results on a
diverse array of downstream NLP tasks. Building on recent token-level probing
work, we introduce a novel edge probing task design and construct a broad suite
of sub-sentence tasks derived from the traditional structured NLP pipeline. We
probe word-level contextual representations from four recent models and
investigate how they encode sentence structure across a range of syntactic,
semantic, local, and long-range phenomena. We find that existing models trained
on language modeling and translation produce strong representations for
syntactic phenomena, but only offer comparably small improvements on semantic
tasks over a non-contextual baseline.