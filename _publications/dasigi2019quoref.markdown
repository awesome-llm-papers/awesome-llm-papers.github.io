---
layout: publication
title: 'Quoref: A Reading Comprehension Dataset With Questions Requiring Coreferential
  Reasoning'
authors: "Pradeep Dasigi, Nelson F. Liu, Ana Marasovi\u0107, Noah A. Smith, Matt Gardner"
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: dasigi2019quoref
citations: 163
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.05803'}]
tags: ["Datasets", "EMNLP"]
short_authors: Dasigi et al.
---
Machine comprehension of texts longer than a single sentence often requires
coreference resolution. However, most current reading comprehension benchmarks
do not contain complex coreferential phenomena and hence fail to evaluate the
ability of models to resolve coreference. We present a new crowdsourced dataset
containing more than 24K span-selection questions that require resolving
coreference among entities in over 4.7K English paragraphs from Wikipedia.
Obtaining questions focused on such phenomena is challenging, because it is
hard to avoid lexical cues that shortcut complex reasoning. We deal with this
issue by using a strong baseline model as an adversary in the crowdsourcing
loop, which helps crowdworkers avoid writing questions with exploitable surface
cues. We show that state-of-the-art reading comprehension models perform
significantly worse than humans on this benchmark---the best model performance
is 70.5 F1, while the estimated human performance is 93.4 F1.