---
layout: publication
title: A Reinforced Generation Of Adversarial Examples For Neural Machine Translation
authors: Wei Zou, Shujian Huang, Jun Xie, Xinyu Dai, Jiajun Chen
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: zou2019reinforced
citations: 60
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.03677'}]
tags: ["Security"]
short_authors: Zou et al.
---
Neural machine translation systems tend to fail on less decent inputs despite
its significant efficacy, which may significantly harm the credibility of this
systems-fathoming how and when neural-based systems fail in such cases is
critical for industrial maintenance. Instead of collecting and analyzing bad
cases using limited handcrafted error features, here we investigate this issue
by generating adversarial examples via a new paradigm based on reinforcement
learning. Our paradigm could expose pitfalls for a given performance metric,
e.g., BLEU, and could target any given neural machine translation architecture.
We conduct experiments of adversarial attacks on two mainstream neural machine
translation architectures, RNN-search, and Transformer. The results show that
our method efficiently produces stable attacks with meaning-preserving
adversarial examples. We also present a qualitative and quantitative analysis
for the preference pattern of the attack, demonstrating its capability of
pitfall exposure.