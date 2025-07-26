---
layout: publication
title: Twitter Sentiment Analysis Via Bi-sense Emoji Embedding And Attention-based
  LSTM
authors: Yuxiao Chen, Jianbo Yuan, Quanzeng You, Jiebo Luo
conference: Proceedings of the 26th ACM international conference on Multimedia
year: 2018
bibkey: chen2018twitter
citations: 60
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1807.07961'}]
tags: ["Model Architecture"]
short_authors: Chen et al.
---
Sentiment analysis on large-scale social media data is important to bridge
the gaps between social media contents and real world activities including
political election prediction, individual and public emotional status
monitoring and analysis, and so on. Although textual sentiment analysis has
been well studied based on platforms such as Twitter and Instagram, analysis of
the role of extensive emoji uses in sentiment analysis remains light. In this
paper, we propose a novel scheme for Twitter sentiment analysis with extra
attention on emojis. We first learn bi-sense emoji embeddings under positive
and negative sentimental tweets individually, and then train a sentiment
classifier by attending on these bi-sense emoji embeddings with an
attention-based long short-term memory network (LSTM). Our experiments show
that the bi-sense embedding is effective for extracting sentiment-aware
embeddings of emojis and outperforms the state-of-the-art models. We also
visualize the attentions to show that the bi-sense emoji embedding provides
better guidance on the attention mechanism to obtain a more robust
understanding of the semantics and sentiments.