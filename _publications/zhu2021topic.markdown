---
layout: publication
title: Topic-driven And Knowledge-aware Transformer For Dialogue Emotion Detection
authors: Lixing Zhu, Gabriele Pergola, Lin Gui, Deyu Zhou, Yulan He
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2021
bibkey: zhu2021topic
citations: 107
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2106.01071'}]
tags: ["Model Architecture"]
short_authors: Zhu et al.
---
Emotion detection in dialogues is challenging as it often requires the
identification of thematic topics underlying a conversation, the relevant
commonsense knowledge, and the intricate transition patterns between the
affective states. In this paper, we propose a Topic-Driven Knowledge-Aware
Transformer to handle the challenges above. We firstly design a topic-augmented
language model (LM) with an additional layer specialized for topic detection.
The topic-augmented LM is then combined with commonsense statements derived
from a knowledge base based on the dialogue contextual information. Finally, a
transformer-based encoder-decoder architecture fuses the topical and
commonsense information, and performs the emotion label sequence prediction.
The model has been experimented on four datasets in dialogue emotion detection,
demonstrating its superiority empirically over the existing state-of-the-art
approaches. Quantitative and qualitative results show that the model can
discover topics which help in distinguishing emotion categories.