---
layout: publication
title: Affect-driven Dialog Generation
authors: Pierre Colombo, Wojciech Witon, Ashutosh Modi, James Kennedy, Mubbasir Kapadia
conference: Proceedings of the 2019 Conference of the North
year: 2019
bibkey: colombo2019affect
citations: 107
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.02793'}]
tags: ["Efficiency"]
short_authors: Colombo et al.
---
The majority of current systems for end-to-end dialog generation focus on
response quality without an explicit control over the affective content of the
responses. In this paper, we present an affect-driven dialog system, which
generates emotional responses in a controlled manner using a continuous
representation of emotions. The system achieves this by modeling emotions at a
word and sequence level using: (1) a vector representation of the desired
emotion, (2) an affect regularizer, which penalizes neutral words, and (3) an
affect sampling method, which forces the neural network to generate diverse
words that are emotionally relevant. During inference, we use a reranking
procedure that aims to extract the most emotionally relevant responses using a
human-in-the-loop optimization process. We study the performance of our system
in terms of both quantitative (BLEU score and response diversity), and
qualitative (emotional appropriateness) measures.