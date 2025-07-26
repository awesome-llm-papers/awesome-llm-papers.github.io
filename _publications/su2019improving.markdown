---
layout: publication
title: Improving Multi-turn Dialogue Modelling With Utterance Rewriter
authors: Hui Su, Xiaoyu Shen, Rongzhi Zhang, Fei Sun, Pengwei Hu, Cheng Niu, Jie Zhou
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: su2019improving
citations: 103
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.07004'}]
tags: ["Dialogue & Multi Turn"]
short_authors: Su et al.
---
Recent research has made impressive progress in single-turn dialogue
modelling. In the multi-turn setting, however, current models are still far
from satisfactory. One major challenge is the frequently occurred coreference
and information omission in our daily conversation, making it hard for machines
to understand the real intention. In this paper, we propose rewriting the human
utterance as a pre-process to help multi-turn dialgoue modelling. Each
utterance is first rewritten to recover all coreferred and omitted information.
The next processing steps are then performed based on the rewritten utterance.
To properly train the utterance rewriter, we collect a new dataset with human
annotations and introduce a Transformer-based utterance rewriting architecture
using the pointer network. We show the proposed architecture achieves
remarkably good performance on the utterance rewriting task. The trained
utterance rewriter can be easily integrated into online chatbots and brings
general improvement over different domains.