---
layout: publication
title: A Multi-type Multi-span Network For Reading Comprehension That Requires Discrete
  Reasoning
authors: Minghao Hu, Yuxing Peng, Zhen Huang, Dongsheng Li
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: hu2019multi
citations: 83
additional_links: [{name: Code, url: 'https://github.com/huminghao16/MTMSN\'}, {name: Paper,
    url: 'https://arxiv.org/abs/1908.05514'}]
tags: ["EMNLP", "Has Code"]
short_authors: Hu et al.
---
Rapid progress has been made in the field of reading comprehension and
question answering, where several systems have achieved human parity in some
simplified settings. However, the performance of these models degrades
significantly when they are applied to more realistic scenarios, such as
answers involve various types, multiple text strings are correct answers, or
discrete reasoning abilities are required. In this paper, we introduce the
Multi-Type Multi-Span Network (MTMSN), a neural reading comprehension model
that combines a multi-type answer predictor designed to support various answer
types (e.g., span, count, negation, and arithmetic expression) with a
multi-span extraction method for dynamically producing one or multiple text
spans. In addition, an arithmetic expression reranking mechanism is proposed to
rank expression candidates for further confirming the prediction. Experiments
show that our model achieves 79.9 F1 on the DROP hidden test set, creating new
state-of-the-art results. Source
code\footnote\{https://github.com/huminghao16/MTMSN\} is released to
facilitate future work.