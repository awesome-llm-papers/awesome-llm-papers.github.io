---
layout: publication
title: 'Mojitalk: Generating Emotional Responses At Scale'
authors: Xianda Zhou, William Yang Wang
conference: 'Proceedings of the 56th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2018
bibkey: zhou2017mojitalk
citations: 211
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1711.04090'}]
tags: ["Datasets", "Training Techniques"]
short_authors: Xianda Zhou, William Yang Wang
---
Generating emotional language is a key step towards building empathetic
natural language processing agents. However, a major challenge for this line of
research is the lack of large-scale labeled training data, and previous studies
are limited to only small sets of human annotated sentiment labels.
Additionally, explicitly controlling the emotion and sentiment of generated
text is also difficult. In this paper, we take a more radical approach: we
exploit the idea of leveraging Twitter data that are naturally labeled with
emojis. More specifically, we collect a large corpus of Twitter conversations
that include emojis in the response, and assume the emojis convey the
underlying emotions of the sentence. We then introduce a reinforced conditional
variational encoder approach to train a deep generative model on these
conversations, which allows us to use emojis to control the emotion of the
generated text. Experimentally, we show in our quantitative and qualitative
analyses that the proposed models can successfully generate high-quality
abstractive conversation responses in accordance with designated emotions.