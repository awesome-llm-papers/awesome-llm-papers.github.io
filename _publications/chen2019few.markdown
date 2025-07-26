---
layout: publication
title: Few-shot NLG With Pre-trained Language Model
authors: Zhiyu Chen, Harini Eavani, Wenhu Chen, Yinyin Liu, William Yang Wang
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: chen2019few
citations: 114
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.09521'}]
tags: ["Few-Shot", "Has Code"]
short_authors: Chen et al.
---
Neural-based end-to-end approaches to natural language generation (NLG) from
structured data or knowledge are data-hungry, making their adoption for
real-world applications difficult with limited data. In this work, we propose
the new task of \textit\{few-shot natural language generation\}. Motivated by how
humans tend to summarize tabular data, we propose a simple yet effective
approach and show that it not only demonstrates strong performance but also
provides good generalization across domains. The design of the model
architecture is based on two aspects: content selection from input data and
language modeling to compose coherent sentences, which can be acquired from
prior knowledge. With just 200 training examples, across multiple domains, we
show that our approach achieves very reasonable performances and outperforms
the strongest baseline by an average of over 8.0 BLEU points improvement. Our
code and data can be found at https://github.com/czyssrs/Few-Shot-NLG