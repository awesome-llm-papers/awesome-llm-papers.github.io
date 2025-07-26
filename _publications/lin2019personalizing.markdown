---
layout: publication
title: Personalizing Dialogue Agents Via Meta-learning
authors: Zhaojiang Lin, Andrea Madotto, Chien-sheng Wu, Pascale Fung
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: lin2019personalizing
citations: 183
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1905.10033'}]
tags: ["Datasets", "Evaluation"]
short_authors: Lin et al.
---
Existing personalized dialogue models use human designed persona descriptions
to improve dialogue consistency. Collecting such descriptions from existing
dialogues is expensive and requires hand-crafted feature designs. In this
paper, we propose to extend Model-Agnostic Meta-Learning (MAML)(Finn et al.,
2017) to personalized dialogue learning without using any persona descriptions.
Our model learns to quickly adapt to new personas by leveraging only a few
dialogue samples collected from the same user, which is fundamentally different
from conditioning the response on the persona descriptions. Empirical results
on Persona-chat dataset (Zhang et al., 2018) indicate that our solution
outperforms non-meta-learning baselines using automatic evaluation metrics, and
in terms of human-evaluated fluency and consistency.