---
layout: publication
title: Do Response Selection Models Really Know What's Next? Utterance Manipulation
  Strategies For Multi-turn Response Selection
authors: Taesun Whang et al.
conference: Arxiv
year: 2020
citations: 16
bibkey: whang2020do
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2009.04703'}]
tags: [Training Techniques, Model Architecture, BERT]
---
In this paper, we study the task of selecting the optimal response given a
user and system utterance history in retrieval-based multi-turn dialog systems.
Recently, pre-trained language models (e.g., BERT, RoBERTa, and ELECTRA) showed
significant improvements in various natural language processing tasks. This and
similar response selection tasks can also be solved using such language models
by formulating the tasks as dialog--response binary classification tasks.
Although existing works using this approach successfully obtained
state-of-the-art results, we observe that language models trained in this
manner tend to make predictions based on the relatedness of history and
candidates, ignoring the sequential nature of multi-turn dialog systems. This
suggests that the response selection task alone is insufficient for learning
temporal dependencies between utterances. To this end, we propose utterance
manipulation strategies (UMS) to address this problem. Specifically, UMS
consist of several strategies (i.e., insertion, deletion, and search), which
aid the response selection model towards maintaining dialog coherence. Further,
UMS are self-supervised methods that do not require additional annotation and
thus can be easily incorporated into existing approaches. Extensive evaluation
across multiple languages and models shows that UMS are highly effective in
teaching dialog consistency, which leads to models pushing the state-of-the-art
with significant margins on multiple public benchmark datasets.