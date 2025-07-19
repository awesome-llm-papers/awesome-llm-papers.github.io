---
layout: publication
title: Not All Attention Is All You Need
authors: Wu Hongqiu, Zhao Hai, Zhang Min
conference: Arxiv
year: 2021
bibkey: wu2021not
citations: 59469
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.04692'}]
tags: [Training Techniques, Attention Mechanism, Transformer, Model Architecture,
  Reinforcement Learning]
---
Beyond the success story of pre-trained language models (PrLMs) in recent
natural language processing, they are susceptible to over-fitting due to
unusual large model size. To this end, dropout serves as a therapy. However,
existing methods like random-based, knowledge-based and search-based dropout
are more general but less effective onto self-attention based models, which are
broadly chosen as the fundamental architecture of PrLMs. In this paper, we
propose a novel dropout method named AttendOut to let self-attention empowered
PrLMs capable of more robust task-specific tuning. We demonstrate that
state-of-the-art models with elaborate training design may achieve much
stronger results. We verify the universality of our approach on extensive
natural language processing tasks.