---
layout: publication
title: Contextual Sequence Modeling For Recommendation With Recurrent Neural Networks
authors: Elena Smirnova, Flavian Vasile
conference: Proceedings of the 2nd Workshop on Deep Learning for Recommender Systems
year: 2017
bibkey: smirnova2017contextual
citations: 159
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1706.07684'}]
tags: ["Time Series"]
short_authors: Elena Smirnova, Flavian Vasile
---
Recommendations can greatly benefit from good representations of the user
state at recommendation time. Recent approaches that leverage Recurrent Neural
Networks (RNNs) for session-based recommendations have shown that Deep Learning
models can provide useful user representations for recommendation. However,
current RNN modeling approaches summarize the user state by only taking into
account the sequence of items that the user has interacted with in the past,
without taking into account other essential types of context information such
as the associated types of user-item interactions, the time gaps between events
and the time of day for each interaction. To address this, we propose a new
class of Contextual Recurrent Neural Networks for Recommendation (CRNNs) that
can take into account the contextual information both in the input and output
layers and modifying the behavior of the RNN by combining the context embedding
with the item embedding and more explicitly, in the model dynamics, by
parametrizing the hidden unit transitions as a function of context information.
We compare our CRNNs approach with RNNs and non-sequential baselines and show
good improvements on the next event prediction task.