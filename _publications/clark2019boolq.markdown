---
layout: publication
title: 'Boolq: Exploring The Surprising Difficulty Of Natural Yes/no Questions'
authors: Christopher Clark, Kenton Lee, Ming-wei Chang, Tom Kwiatkowski, Michael Collins,
  Kristina Toutanova
conference: Arxiv
year: 2019
bibkey: clark2019boolq
citations: 203
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1905.10044'}]
tags: ["Datasets"]
short_authors: Clark et al.
---
In this paper we study yes/no questions that are naturally occurring ---
meaning that they are generated in unprompted and unconstrained settings. We
build a reading comprehension dataset, BoolQ, of such questions, and show that
they are unexpectedly challenging. They often query for complex, non-factoid
information, and require difficult entailment-like inference to solve. We also
explore the effectiveness of a range of transfer learning baselines. We find
that transferring from entailment data is more effective than transferring from
paraphrase or extractive QA data, and that it, surprisingly, continues to be
very beneficial even when starting from massive pre-trained language models
such as BERT. Our best method trains BERT on MultiNLI and then re-trains it on
our train set. It achieves 80.4% accuracy compared to 90% accuracy of human
annotators (and 62% majority-baseline), leaving a significant gap for future
work.