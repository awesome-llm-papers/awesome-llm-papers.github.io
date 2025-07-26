---
layout: publication
title: Semantic Graphs For Generating Deep Questions
authors: Liangming Pan, Yuxi Xie, Yansong Feng, Tat-seng Chua, Min-yen Kan
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: pan2020semantic
citations: 73
additional_links: [{name: Code, url: 'https://github.com/WING-NUS/SG-Deep-Question-Generation'},
  {name: Paper, url: 'https://arxiv.org/abs/2004.12704'}]
tags: ["Datasets", "Has Code", "Tools", "Training Techniques"]
short_authors: Pan et al.
---
This paper proposes the problem of Deep Question Generation (DQG), which aims
to generate complex questions that require reasoning over multiple pieces of
information of the input passage. In order to capture the global structure of
the document and facilitate reasoning, we propose a novel framework which first
constructs a semantic-level graph for the input document and then encodes the
semantic graph by introducing an attention-based GGNN (Att-GGNN). Afterwards,
we fuse the document-level and graph-level representations to perform joint
training of content selection and question decoding. On the HotpotQA
deep-question centric dataset, our model greatly improves performance over
questions requiring reasoning over multiple facts, leading to state-of-the-art
performance. The code is publicly available at
https://github.com/WING-NUS/SG-Deep-Question-Generation.