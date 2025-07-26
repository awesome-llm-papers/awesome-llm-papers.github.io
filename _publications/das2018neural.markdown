---
layout: publication
title: Neural Modular Control For Embodied Question Answering
authors: Abhishek Das, Georgia Gkioxari, Stefan Lee, Devi Parikh, Dhruv Batra
conference: Arxiv
year: 2018
bibkey: das2018neural
citations: 78
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1810.11181'}]
tags: ["Reinforcement Learning"]
short_authors: Das et al.
---
We present a modular approach for learning policies for navigation over long
planning horizons from language input. Our hierarchical policy operates at
multiple timescales, where the higher-level master policy proposes subgoals to
be executed by specialized sub-policies. Our choice of subgoals is
compositional and semantic, i.e. they can be sequentially combined in arbitrary
orderings, and assume human-interpretable descriptions (e.g. 'exit room', 'find
kitchen', 'find refrigerator', etc.).
  We use imitation learning to warm-start policies at each level of the
hierarchy, dramatically increasing sample efficiency, followed by reinforcement
learning. Independent reinforcement learning at each level of hierarchy enables
sub-policies to adapt to consequences of their actions and recover from errors.
Subsequent joint hierarchical training enables the master policy to adapt to
the sub-policies.
  On the challenging EQA (Das et al., 2018) benchmark in House3D (Wu et al.,
2018), requiring navigating diverse realistic indoor environments, our approach
outperforms prior work by a significant margin, both in terms of navigation and
question answering.