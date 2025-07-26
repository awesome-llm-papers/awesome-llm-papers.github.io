---
layout: publication
title: Better Fine-tuning By Reducing Representational Collapse
authors: Armen Aghajanyan, Akshat Shrivastava, Anchit Gupta, Naman Goyal, Luke Zettlemoyer,
  Sonal Gupta
conference: Arxiv
year: 2020
bibkey: aghajanyan2020better
citations: 103
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2008.03156'}]
tags: ["Fine-Tuning"]
short_authors: Aghajanyan et al.
---
Although widely adopted, existing approaches for fine-tuning pre-trained
language models have been shown to be unstable across hyper-parameter settings,
motivating recent work on trust region methods. In this paper, we present a
simplified and efficient method rooted in trust region theory that replaces
previously used adversarial objectives with parametric noise (sampling from
either a normal or uniform distribution), thereby discouraging representation
change during fine-tuning when possible without hurting performance. We also
introduce a new analysis to motivate the use of trust region methods more
generally, by studying representational collapse; the degradation of
generalizable representations from pre-trained models as they are fine-tuned
for a specific end task. Extensive experiments show that our fine-tuning method
matches or exceeds the performance of previous trust region methods on a range
of understanding and generation tasks (including DailyMail/CNN, Gigaword,
Reddit TIFU, and the GLUE benchmark), while also being much faster. We also
show that it is less prone to representation collapse; the pre-trained models
maintain more generalizable representations every time they are fine-tuned.