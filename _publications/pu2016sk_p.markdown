---
layout: publication
title: 'Sk_p: A Neural Program Corrector For Moocs'
authors: Yewen Pu, Karthik Narasimhan, Armando Solar-lezama, Regina Barzilay
conference: 'Companion Proceedings of the 2016 ACM SIGPLAN International Conference
  on Systems, Programming, Languages and Applications: Software for Humanity'
year: 2016
bibkey: pu2016sk_p
citations: 121
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1607.02902'}]
tags: ["Applications"]
short_authors: Pu et al.
---
We present a novel technique for automatic program correction in MOOCs,
capable of fixing both syntactic and semantic errors without manual, problem
specific correction strategies. Given an incorrect student program, it
generates candidate programs from a distribution of likely corrections, and
checks each candidate for correctness against a test suite.
  The key observation is that in MOOCs many programs share similar code
fragments, and the seq2seq neural network model, used in the natural-language
processing task of machine translation, can be modified and trained to recover
these fragments.
  Experiment shows our scheme can correct 29% of all incorrect submissions and
out-performs state of the art approach which requires manual, problem specific
correction strategies.