---
layout: publication
title: Multilingual Part-of-speech Tagging With Bidirectional Long Short-term Memory
  Models And Auxiliary Loss
authors: "Barbara Plank, Anders S\xF8gaard, Yoav Goldberg"
conference: 'Proceedings of the 54th Annual Meeting of the Association for Computational
  Linguistics (Volume 2: Short Papers)'
year: 2016
bibkey: plank2016multilingual
citations: 473
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1604.05529'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: "Barbara Plank, Anders S\xF8gaard, Yoav Goldberg"
---
Bidirectional long short-term memory (bi-LSTM) networks have recently proven
successful for various NLP sequence modeling tasks, but little is known about
their reliance to input representations, target languages, data set size, and
label noise. We address these issues and evaluate bi-LSTMs with word,
character, and unicode byte embeddings for POS tagging. We compare bi-LSTMs to
traditional POS taggers across languages and data sizes. We also present a
novel bi-LSTM model, which combines the POS tagging loss function with an
auxiliary loss function that accounts for rare words. The model obtains
state-of-the-art performance across 22 languages, and works especially well for
morphologically complex languages. Our analysis suggests that bi-LSTMs are less
sensitive to training data size and label corruptions (at small noise levels)
than previously assumed.