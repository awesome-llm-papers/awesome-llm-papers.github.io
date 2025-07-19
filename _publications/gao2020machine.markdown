---
layout: publication
title: 'From Machine Reading Comprehension To Dialogue State Tracking: Bridging The
  Gap'
authors: Gao et al.
conference: Proceedings of the 2nd Workshop on Natural Language Processing for Conversational
  AI
year: 2020
bibkey: gao2020machine
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.05827'}]
tags: [RAG, Training Techniques, Model Architecture, Few Shot, Datasets, TACL]
---
Dialogue state tracking (DST) is at the heart of task-oriented dialogue
systems. However, the scarcity of labeled data is an obstacle to building
accurate and robust state tracking systems that work across a variety of
domains. Existing approaches generally require some dialogue data with state
information and their ability to generalize to unknown domains is limited. In
this paper, we propose using machine reading comprehension (RC) in state
tracking from two perspectives: model architectures and datasets. We divide the
slot types in dialogue state into categorical or extractive to borrow the
advantages from both multiple-choice and span-based reading comprehension
models. Our method achieves near the current state-of-the-art in joint goal
accuracy on MultiWOZ 2.1 given full training data. More importantly, by
leveraging machine reading comprehension datasets, our method outperforms the
existing approaches by many a large margin in few-shot scenarios when the
availability of in-domain data is limited. Lastly, even without any state
tracking data, i.e., zero-shot scenario, our proposed approach achieves greater
than 90% average slot accuracy in 12 out of 30 slots in MultiWOZ 2.1.