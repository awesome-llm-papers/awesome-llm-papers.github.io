---
layout: publication
title: 'Coach: A Coarse-to-fine Approach For Cross-domain Slot Filling'
authors: Zihan Liu, Genta Indra Winata, Peng Xu, Pascale Fung
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: liu2020coach
citations: 98
additional_links: [{name: Code, url: 'https://github.com/zliucr/coach'}, {name: Paper,
    url: 'https://arxiv.org/abs/2004.11727'}]
tags: ["Training Techniques"]
short_authors: Liu et al.
---
As an essential task in task-oriented dialog systems, slot filling requires
extensive training data in a certain domain. However, such data are not always
available. Hence, cross-domain slot filling has naturally arisen to cope with
this data scarcity problem. In this paper, we propose a Coarse-to-fine approach
(Coach) for cross-domain slot filling. Our model first learns the general
pattern of slot entities by detecting whether the tokens are slot entities or
not. It then predicts the specific types for the slot entities. In addition, we
propose a template regularization approach to improve the adaptation robustness
by regularizing the representation of utterances based on utterance templates.
Experimental results show that our model significantly outperforms
state-of-the-art approaches in slot filling. Furthermore, our model can also be
applied to the cross-domain named entity recognition task, and it achieves
better adaptation performance than other existing baselines. The code is
available at https://github.com/zliucr/coach.