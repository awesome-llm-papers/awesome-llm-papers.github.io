---
layout: publication
title: 'Multiconer: A Large-scale Multilingual Dataset For Complex Named Entity Recognition'
authors: Shervin Malmasi, Anjie Fang, Besnik Fetahu, Sudipta Kar, Oleg Rokhlenko
conference: Arxiv
year: 2022
bibkey: malmasi2022multiconer
citations: 78
additional_links: [{name: Code, url: 'https://registry.opendata.aws/multiconer/'},
  {name: Paper, url: 'https://arxiv.org/abs/2208.14536'}]
tags: ["Datasets"]
short_authors: Malmasi et al.
---
We present MultiCoNER, a large multilingual dataset for Named Entity
Recognition that covers 3 domains (Wiki sentences, questions, and search
queries) across 11 languages, as well as multilingual and code-mixing subsets.
This dataset is designed to represent contemporary challenges in NER, including
low-context scenarios (short and uncased text), syntactically complex entities
like movie titles, and long-tail entity distributions. The 26M token dataset is
compiled from public resources using techniques such as heuristic-based
sentence sampling, template extraction and slotting, and machine translation.
We applied two NER models on our dataset: a baseline XLM-RoBERTa model, and a
state-of-the-art GEMNET model that leverages gazetteers. The baseline achieves
moderate performance (macro-F1=54%), highlighting the difficulty of our data.
GEMNET, which uses gazetteers, improvement significantly (average improvement
of macro-F1=+30%). MultiCoNER poses challenges even for large pre-trained
language models, and we believe that it can help further research in building
robust NER systems. MultiCoNER is publicly available at
https://registry.opendata.aws/multiconer/ and we hope that this resource will
help advance research in various aspects of NER.