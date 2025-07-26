---
layout: publication
title: 'Ambigqa: Answering Ambiguous Open-domain Questions'
authors: Sewon Min, Julian Michael, Hannaneh Hajishirzi, Luke Zettlemoyer
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: min2020ambigqa
citations: 154
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.10645'}]
tags: ["EMNLP"]
short_authors: Min et al.
---
Ambiguity is inherent to open-domain question answering; especially when
exploring new topics, it can be difficult to ask questions that have a single,
unambiguous answer. In this paper, we introduce AmbigQA, a new open-domain
question answering task which involves finding every plausible answer, and then
rewriting the question for each one to resolve the ambiguity. To study this
task, we construct AmbigNQ, a dataset covering 14,042 questions from NQ-open,
an existing open-domain QA benchmark. We find that over half of the questions
in NQ-open are ambiguous, with diverse sources of ambiguity such as event and
entity references. We also present strong baseline models for AmbigQA which we
show benefit from weakly supervised learning that incorporates NQ-open,
strongly suggesting our new task and data will support significant future
research effort. Our data and baselines are available at
https://nlp.cs.washington.edu/ambigqa.