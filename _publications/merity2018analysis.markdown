---
layout: publication
title: An Analysis Of Neural Language Modeling At Multiple Scales
authors: Stephen Merity, Nitish Shirish Keskar, Richard Socher
conference: Arxiv
year: 2018
bibkey: merity2018analysis
citations: 161
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1803.08240'}]
tags: ["Datasets"]
short_authors: Stephen Merity, Nitish Shirish Keskar, Richard Socher
---
Many of the leading approaches in language modeling introduce novel, complex
and specialized architectures. We take existing state-of-the-art word level
language models based on LSTMs and QRNNs and extend them to both larger
vocabularies as well as character-level granularity. When properly tuned, LSTMs
and QRNNs achieve state-of-the-art results on character-level (Penn Treebank,
enwik8) and word-level (WikiText-103) datasets, respectively. Results are
obtained in only 12 hours (WikiText-103) to 2 days (enwik8) using a single
modern GPU.