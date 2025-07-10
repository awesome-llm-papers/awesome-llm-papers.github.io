---
layout: publication
title: 'Juice: A Large Scale Distantly Supervised Dataset For Open Domain Context-based
  Code Generation'
authors: Rajas Agashe, Srinivasan Iyer, Luke Zettlemoyer
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
citations: 20
bibkey: agashe2019large
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1910.02216'}]
tags: [Tools, Training Techniques, Evaluation, Reinforcement Learning]
---
Interactive programming with interleaved code snippet cells and natural
language markdown is recently gaining popularity in the form of Jupyter
notebooks, which accelerate prototyping and collaboration. To study code
generation conditioned on a long context history, we present JuICe, a corpus of
1.5 million examples with a curated test set of 3.7K instances based on online
programming assignments. Compared with existing contextual code generation
datasets, JuICe provides refined human-curated data, open-domain code, and an
order of magnitude more training data. Using JuICe, we train models for two
tasks: (1) generation of the API call sequence in a code cell, and (2) full
code cell generation, both conditioned on the NL-Code history up to a
particular code cell. Experiments using current baseline code generation models
show that both context and distant supervision aid in generation, and that the
dataset is challenging for current systems.