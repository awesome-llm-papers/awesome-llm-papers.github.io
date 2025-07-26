---
layout: publication
title: A Contextual Hierarchical Attention Network With Adaptive Objective For Dialogue
  State Tracking
authors: Yong Shan, Zekang Li, Jinchao Zhang, Fandong Meng, Yang Feng, Cheng Niu,
  Jie Zhou
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: shan2020contextual
citations: 62
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2006.01554'}]
tags: ["Training Techniques"]
short_authors: Shan et al.
---
Recent studies in dialogue state tracking (DST) leverage historical
information to determine states which are generally represented as slot-value
pairs. However, most of them have limitations to efficiently exploit relevant
context due to the lack of a powerful mechanism for modeling interactions
between the slot and the dialogue history. Besides, existing methods usually
ignore the slot imbalance problem and treat all slots indiscriminately, which
limits the learning of hard slots and eventually hurts overall performance. In
this paper, we propose to enhance the DST through employing a contextual
hierarchical attention network to not only discern relevant information at both
word level and turn level but also learn contextual representations. We further
propose an adaptive objective to alleviate the slot imbalance problem by
dynamically adjust weights of different slots during training. Experimental
results show that our approach reaches 52.68% and 58.55% joint accuracy on
MultiWOZ 2.0 and MultiWOZ 2.1 datasets respectively and achieves new
state-of-the-art performance with considerable improvements (+1.24% and
+5.98%).