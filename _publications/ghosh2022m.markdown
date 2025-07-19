---
layout: publication
title: 'M-MELD: A Multilingual Multi-party Dataset For Emotion Recognition In Conversations'
authors: Ghosh et al.
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2022
bibkey: ghosh2022m
citations: 526
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.16799'}]
tags: [Model Architecture, Merging, ACL, Multimodal Models, Datasets]
---
Expression of emotions is a crucial part of daily human communication.
Emotion recognition in conversations (ERC) is an emerging field of study, where
the primary task is to identify the emotion behind each utterance in a
conversation. Though a lot of work has been done on ERC in the past, these
works only focus on ERC in the English language, thereby ignoring any other
languages. In this paper, we present Multilingual MELD (M-MELD), where we
extend the Multimodal EmotionLines Dataset (MELD) \cite\{poria2018meld\} to 4
other languages beyond English, namely Greek, Polish, French, and Spanish.
Beyond just establishing strong baselines for all of these 4 languages, we also
propose a novel architecture, DiscLSTM, that uses both sequential and
conversational discourse context in a conversational dialogue for ERC. Our
proposed approach is computationally efficient, can transfer across languages
using just a cross-lingual encoder, and achieves better performance than most
uni-modal text approaches in the literature on both MELD and M-MELD. We make
our data and code publicly on GitHub.