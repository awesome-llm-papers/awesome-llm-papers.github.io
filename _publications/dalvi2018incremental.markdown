---
layout: publication
title: Incremental Decoding And Training Methods For Simultaneous Translation In Neural
  Machine Translation
authors: Fahim Dalvi, Nadir Durrani, Hassan Sajjad, Stephan Vogel
conference: 'Proceedings of the 2018 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies, Volume 2
  (Short Papers)'
year: 2018
bibkey: dalvi2018incremental
citations: 108
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1806.03661'}]
tags: ["NAACL", "Training Techniques"]
short_authors: Dalvi et al.
---
We address the problem of simultaneous translation by modifying the Neural MT
decoder to operate with dynamically built encoder and attention. We propose a
tunable agent which decides the best segmentation strategy for a user-defined
BLEU loss and Average Proportion (AP) constraint. Our agent outperforms
previously proposed Wait-if-diff and Wait-if-worse agents (Cho and Esipova,
2016) on BLEU with a lower latency. Secondly we proposed data-driven changes to
Neural MT training to better match the incremental decoding framework.