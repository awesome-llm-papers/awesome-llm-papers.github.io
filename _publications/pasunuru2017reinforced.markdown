---
layout: publication
title: Reinforced Video Captioning With Entailment Rewards
authors: Ramakanth Pasunuru, Mohit Bansal
conference: Proceedings of the 2017 Conference on Empirical Methods in Natural Language
  Processing
year: 2017
bibkey: pasunuru2017reinforced
citations: 120
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1708.02300'}]
tags: ["Reinforcement Learning"]
short_authors: Ramakanth Pasunuru, Mohit Bansal
---
Sequence-to-sequence models have shown promising improvements on the temporal
task of video captioning, but they optimize word-level cross-entropy loss
during training. First, using policy gradient and mixed-loss methods for
reinforcement learning, we directly optimize sentence-level task-based metrics
(as rewards), achieving significant improvements over the baseline, based on
both automatic metrics and human evaluation on multiple datasets. Next, we
propose a novel entailment-enhanced reward (CIDEnt) that corrects
phrase-matching based metrics (such as CIDEr) to only allow for
logically-implied partial matches and avoid contradictions, achieving further
significant improvements over the CIDEr-reward model. Overall, our
CIDEnt-reward model achieves the new state-of-the-art on the MSR-VTT dataset.