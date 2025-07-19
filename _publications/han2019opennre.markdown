---
layout: publication
title: 'Opennre: An Open And Extensible Toolkit For Neural Relation Extraction'
authors: Han et al.
conference: 'Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP): System Demonstrations'
year: 2019
bibkey: han2019opennre
citations: 127
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.13078'}]
tags: [Training Techniques, EMNLP, Tools, Reinforcement Learning, Applications]
---
OpenNRE is an open-source and extensible toolkit that provides a unified
framework to implement neural models for relation extraction (RE).
Specifically, by implementing typical RE methods, OpenNRE not only allows
developers to train custom models to extract structured relational facts from
the plain text but also supports quick model validation for researchers.
Besides, OpenNRE provides various functional RE modules based on both
TensorFlow and PyTorch to maintain sufficient modularity and extensibility,
making it becomes easy to incorporate new models into the framework. Besides
the toolkit, we also release an online system to meet real-time extraction
without any training and deploying. Meanwhile, the online system can extract
facts in various scenarios as well as aligning the extracted facts to Wikidata,
which may benefit various downstream knowledge-driven applications (e.g.,
information retrieval and question answering). More details of the toolkit and
online system can be obtained from http://github.com/thunlp/OpenNRE.