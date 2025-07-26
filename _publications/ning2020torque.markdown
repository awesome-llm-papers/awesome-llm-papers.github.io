---
layout: publication
title: 'TORQUE: A Reading Comprehension Dataset Of Temporal Ordering Questions'
authors: Qiang Ning, Hao Wu, Rujun Han, Nanyun Peng, Matt Gardner, Dan Roth
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: ning2020torque
citations: 81
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.00242'}]
tags: ["Datasets", "EMNLP"]
short_authors: Ning et al.
---
A critical part of reading is being able to understand the temporal
relationships between events described in a passage of text, even when those
relationships are not explicitly stated. However, current machine reading
comprehension benchmarks have practically no questions that test temporal
phenomena, so systems trained on these benchmarks have no capacity to answer
questions such as "what happened before/after [some event]?" We introduce
TORQUE, a new English reading comprehension benchmark built on 3.2k news
snippets with 21k human-generated questions querying temporal relationships.
Results show that RoBERTa-large achieves an exact-match score of 51% on the
test set of TORQUE, about 30% behind human performance.