---
layout: publication
title: Machine Comprehension By Text-to-text Neural Question Generation
authors: Xingdi Yuan, Tong Wang, Caglar Gulcehre, Alessandro Sordoni, Philip Bachman,
  Sandeep Subramanian, Saizheng Zhang, Adam Trischler
conference: Proceedings of the 2nd Workshop on Representation Learning for NLP
year: 2017
bibkey: yuan2017machine
citations: 166
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1705.02012'}]
tags: ["Datasets"]
short_authors: Yuan et al.
---
We propose a recurrent neural model that generates natural-language questions
from documents, conditioned on answers. We show how to train the model using a
combination of supervised and reinforcement learning. After teacher forcing for
standard maximum likelihood training, we fine-tune the model using policy
gradient techniques to maximize several rewards that measure question quality.
Most notably, one of these rewards is the performance of a question-answering
system. We motivate question generation as a means to improve the performance
of question answering systems. Our model is trained and evaluated on the recent
question-answering dataset SQuAD.