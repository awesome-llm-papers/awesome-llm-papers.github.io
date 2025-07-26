---
layout: publication
title: Global-locally Self-attentive Dialogue State Tracker
authors: Victor Zhong, Caiming Xiong, Richard Socher
conference: Arxiv
year: 2018
bibkey: zhong2018global
citations: 76
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1805.09655'}]
tags: ["Dialogue & Multi Turn"]
short_authors: Victor Zhong, Caiming Xiong, Richard Socher
---
Dialogue state tracking, which estimates user goals and requests given the
dialogue context, is an essential part of task-oriented dialogue systems. In
this paper, we propose the Global-Locally Self-Attentive Dialogue State Tracker
(GLAD), which learns representations of the user utterance and previous system
actions with global-local modules. Our model uses global modules to share
parameters between estimators for different types (called slots) of dialogue
states, and uses local modules to learn slot-specific features. We show that
this significantly improves tracking of rare states and achieves
state-of-the-art performance on the WoZ and DSTC2 state tracking tasks. GLAD
obtains 88.1% joint goal accuracy and 97.1% request accuracy on WoZ,
outperforming prior work by 3.7% and 5.5%. On DSTC2, our model obtains 74.5%
joint goal accuracy and 97.5% request accuracy, outperforming prior work by
1.1% and 1.0%.