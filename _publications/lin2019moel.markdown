---
layout: publication
title: 'Moel: Mixture Of Empathetic Listeners'
authors: Zhaojiang Lin, Andrea Madotto, Jamin Shin, Peng Xu, Pascale Fung
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: lin2019moel
citations: 190
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.07687'}]
tags: ["EMNLP"]
short_authors: Lin et al.
---
Previous research on empathetic dialogue systems has mostly focused on
generating responses given certain emotions. However, being empathetic not only
requires the ability of generating emotional responses, but more importantly,
requires the understanding of user emotions and replying appropriately. In this
paper, we propose a novel end-to-end approach for modeling empathy in dialogue
systems: Mixture of Empathetic Listeners (MoEL). Our model first captures the
user emotions and outputs an emotion distribution. Based on this, MoEL will
softly combine the output states of the appropriate Listener(s), which are each
optimized to react to certain emotions, and generate an empathetic response.
Human evaluations on empathetic-dialogues (Rashkin et al., 2018) dataset
confirm that MoEL outperforms multitask training baseline in terms of empathy,
relevance, and fluency. Furthermore, the case study on generated responses of
different Listeners shows high interpretability of our model.