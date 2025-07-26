---
layout: publication
title: 'Cosmos QA: Machine Reading Comprehension With Contextual Commonsense Reasoning'
authors: Lifu Huang, Ronan Le Bras, Chandra Bhagavatula, Yejin Choi
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: huang2019cosmos
citations: 268
additional_links: [{name: Code, url: 'https://wilburone.github.io/cosmos'}, {name: Paper,
    url: 'https://arxiv.org/abs/1909.00277'}]
tags: ["Datasets", "EMNLP", "Evaluation", "Model Architecture"]
short_authors: Huang et al.
---
Understanding narratives requires reading between the lines, which in turn,
requires interpreting the likely causes and effects of events, even when they
are not mentioned explicitly. In this paper, we introduce Cosmos QA, a
large-scale dataset of 35,600 problems that require commonsense-based reading
comprehension, formulated as multiple-choice questions. In stark contrast to
most existing reading comprehension datasets where the questions focus on
factual and literal understanding of the context paragraph, our dataset focuses
on reading between the lines over a diverse collection of people's everyday
narratives, asking such questions as "what might be the possible reason of
...?", or "what would have happened if ..." that require reasoning beyond the
exact text spans in the context. To establish baseline performances on Cosmos
QA, we experiment with several state-of-the-art neural architectures for
reading comprehension, and also propose a new architecture that improves over
the competitive baselines. Experimental results demonstrate a significant gap
between machine (68.4%) and human performance (94%), pointing to avenues for
future research on commonsense machine comprehension. Dataset, code and
leaderboard is publicly available at https://wilburone.github.io/cosmos.