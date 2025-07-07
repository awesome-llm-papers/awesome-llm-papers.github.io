---
layout: publication
title: 'Quality: Question Answering With Long Input Texts, Yes!'
authors: Richard Yuanzhe Pang et al.
conference: Arxiv
year: 2021
citations: 15
bibkey: pang2021question
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2112.08608'}]
tags: [RAG, Reinforcement Learning]
---
To enable building and testing models on long-document comprehension, we
introduce QuALITY, a multiple-choice QA dataset with context passages in
English that have an average length of about 5,000 tokens, much longer than
typical current models can process. Unlike in prior work with passages, our
questions are written and validated by contributors who have read the entire
passage, rather than relying on summaries or excerpts. In addition, only half
of the questions are answerable by annotators working under tight time
constraints, indicating that skimming and simple search are not enough to
consistently perform well. Our baseline models perform poorly on this task
(55.4%) and significantly lag behind human performance (93.5%).