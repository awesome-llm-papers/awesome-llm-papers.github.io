---
layout: publication
title: Curriculum Learning And Minibatch Bucketing In Neural Machine Translation
authors: Tom Kocmi, Ondrej Bojar
conference: RANLP 2017 - Recent Advances in Natural Language Processing Meet Deep
  Learning
year: 2017
bibkey: kocmi2017curriculum
citations: 97
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1707.09533'}]
tags: ["Training Techniques"]
short_authors: Tom Kocmi, Ondrej Bojar
---
We examine the effects of particular orderings of sentence pairs on the
on-line training of neural machine translation (NMT). We focus on two types of
such orderings: (1) ensuring that each minibatch contains sentences similar in
some aspect and (2) gradual inclusion of some sentence types as the training
progresses (so called "curriculum learning"). In our English-to-Czech
experiments, the internal homogeneity of minibatches has no effect on the
training but some of our "curricula" achieve a small improvement over the
baseline.