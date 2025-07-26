---
layout: publication
title: 'Cleanrl: High-quality Single-file Implementations Of Deep Reinforcement Learning
  Algorithms'
authors: Shengyi Huang, Rousslan Fernand Julien Dossa, Chang Ye, Jeff Braga
conference: Arxiv
year: 2021
bibkey: huang2021cleanrl
citations: 62
additional_links: [{name: Code, url: 'https://github.com/vwxyzjn/cleanrl'}, {name: Paper,
    url: 'https://arxiv.org/abs/2111.08819'}]
tags: ["Evaluation", "Has Code", "Reinforcement Learning", "Tools"]
short_authors: Huang et al.
---
CleanRL is an open-source library that provides high-quality single-file
implementations of Deep Reinforcement Learning algorithms. It provides a
simpler yet scalable developing experience by having a straightforward codebase
and integrating production tools to help interact and scale experiments. In
CleanRL, we put all details of an algorithm into a single file, making these
performance-relevant details easier to recognize. Additionally, an experiment
tracking feature is available to help log metrics, hyperparameters, videos of
an agent's gameplay, dependencies, and more to the cloud. Despite succinct
implementations, we have also designed tools to help scale, at one point
orchestrating experiments on more than 2000 machines simultaneously via Docker
and cloud providers. Finally, we have ensured the quality of the
implementations by benchmarking against a variety of environments. The source
code of CleanRL can be found at https://github.com/vwxyzjn/cleanrl