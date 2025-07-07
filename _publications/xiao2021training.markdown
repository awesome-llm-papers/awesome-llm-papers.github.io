---
layout: publication
title: Training Large-scale News Recommenders With Pretrained Language Models In The
  Loop
authors: Shitao Xiao, Zheng Liu, Yingxia Shao, Tao Di, Xing Xie
conference: Arxiv
year: 2021
citations: 23
bibkey: xiao2021training
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2102.09268'}]
tags: [Training Techniques, RAG, RecSys, Tools, Reinforcement Learning, BERT, Efficiency
    and Optimization, Model Architecture]
---
News recommendation calls for deep insights of news articles' underlying
semantics. Therefore, pretrained language models (PLMs), like BERT and RoBERTa,
may substantially contribute to the recommendation quality. However, it's
extremely challenging to have news recommenders trained together with such big
models: the learning of news recommenders requires intensive news encoding
operations, whose cost is prohibitive if PLMs are used as the news encoder. In
this paper, we propose a novel framework, \{SpeedyFeed\}, which efficiently
trains PLMs-based news recommenders of superior quality. SpeedyFeed is
highlighted for its light-weighted encoding pipeline, which gives rise to three
major advantages. Firstly, it makes the intermedia results fully reusable for
the training workflow, which removes most of the repetitive but redundant
encoding operations. Secondly, it improves the data efficiency of the training
workflow, where non-informative data can be eliminated from encoding. Thirdly,
it further saves the cost by leveraging simplified news encoding and compact
news representation. Extensive experiments show that SpeedyFeed leads to more
than 100\\(\times\\) acceleration of the training process, which enables big models
to be trained efficiently and effectively over massive user data. The
well-trained PLMs-based model from SpeedyFeed demonstrates highly competitive
performance, where it outperforms the state-of-the-art news recommenders with
significant margins. SpeedyFeed is also a model-agnostic framework, which is
potentially applicable to a wide spectrum of content-based recommender systems;
therefore, the whole framework is open-sourced to facilitate the progress in
related areas.