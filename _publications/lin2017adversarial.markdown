---
layout: publication
title: Adversarial Ranking For Language Generation
authors: Kevin Lin, Dianqi Li, Xiaodong He, Zhengyou Zhang, Ming-ting Sun
conference: Arxiv
year: 2017
bibkey: lin2017adversarial
citations: 192
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1705.11001'}]
tags: ["Datasets", "Reinforcement Learning", "Security", "Training Techniques"]
short_authors: Lin et al.
---
Generative adversarial networks (GANs) have great successes on synthesizing
data. However, the existing GANs restrict the discriminator to be a binary
classifier, and thus limit their learning capacity for tasks that need to
synthesize output with rich structures such as natural language descriptions.
In this paper, we propose a novel generative adversarial network, RankGAN, for
generating high-quality language descriptions. Rather than training the
discriminator to learn and assign absolute binary predicate for individual data
sample, the proposed RankGAN is able to analyze and rank a collection of
human-written and machine-written sentences by giving a reference group. By
viewing a set of data samples collectively and evaluating their quality through
relative ranking scores, the discriminator is able to make better assessment
which in turn helps to learn a better generator. The proposed RankGAN is
optimized through the policy gradient technique. Experimental results on
multiple public datasets clearly demonstrate the effectiveness of the proposed
approach.