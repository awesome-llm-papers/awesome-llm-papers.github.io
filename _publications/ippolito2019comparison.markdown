---
layout: publication
title: Comparison Of Diverse Decoding Methods From Conditional Language Models
authors: "Daphne Ippolito, Reno Kriz, Maria Kustikova, Jo\xE3o Sedoc, Chris Callison-burch"
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: ippolito2019comparison
citations: 88
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.06362'}]
tags: ["Applications", "Survey Paper"]
short_authors: Ippolito et al.
---
While conditional language models have greatly improved in their ability to
output high-quality natural language, many NLP applications benefit from being
able to generate a diverse set of candidate sequences. Diverse decoding
strategies aim to, within a given-sized candidate list, cover as much of the
space of high-quality outputs as possible, leading to improvements for tasks
that re-rank and combine candidate outputs. Standard decoding methods, such as
beam search, optimize for generating high likelihood sequences rather than
diverse ones, though recent work has focused on increasing diversity in these
methods. In this work, we perform an extensive survey of decoding-time
strategies for generating diverse outputs from conditional language models. We
also show how diversity can be improved without sacrificing quality by
over-sampling additional candidates, then filtering to the desired number.