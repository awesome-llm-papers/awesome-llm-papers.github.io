---
layout: publication
title: 'Humor Detection: A Transformer Gets The Last Laugh'
authors: Orion Weller, Kevin Seppi
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: weller2019humor
citations: 105
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.00252'}]
tags: ["EMNLP", "Model Architecture"]
short_authors: Orion Weller, Kevin Seppi
---
Much previous work has been done in attempting to identify humor in text. In
this paper we extend that capability by proposing a new task: assessing whether
or not a joke is humorous. We present a novel way of approaching this problem
by building a model that learns to identify humorous jokes based on ratings
gleaned from Reddit pages, consisting of almost 16,000 labeled instances. Using
these ratings to determine the level of humor, we then employ a Transformer
architecture for its advantages in learning from sentence context. We
demonstrate the effectiveness of this approach and show results that are
comparable to human performance. We further demonstrate our model's increased
capabilities on humor identification problems, such as the previously created
datasets for short jokes and puns. These experiments show that this method
outperforms all previous work done on these tasks, with an F-measure of 93.1%
for the Puns dataset and 98.6% on the Short Jokes dataset.