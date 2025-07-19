---
layout: publication
title: 'CARCA: Context And Attribute-aware Next-item Recommendation Via Cross-attention'
authors: Rashed Ahmed, Elsayed Shereen, Schmidt-thieme Lars
conference: Proceedings of the 16th ACM Conference on Recommender Systems
year: 2022
bibkey: rashed2022carca
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2204.06519'}]
tags: [Model Architecture, RecSys, Transformer, Datasets, Reinforcement Learning,
  Attention Mechanism]
---
In sparse recommender settings, users' context and item attributes play a
crucial role in deciding which items to recommend next. Despite that, recent
works in sequential and time-aware recommendations usually either ignore both
aspects or only consider one of them, limiting their predictive performance. In
this paper, we address these limitations by proposing a context and
attribute-aware recommender model (CARCA) that can capture the dynamic nature
of the user profiles in terms of contextual features and item attributes via
dedicated multi-head self-attention blocks that extract profile-level features
and predicting item scores. Also, unlike many of the current state-of-the-art
sequential item recommendation approaches that use a simple dot-product between
the most recent item's latent features and the target items embeddings for
scoring, CARCA uses cross-attention between all profile items and the target
items to predict their final scores. This cross-attention allows CARCA to
harness the correlation between old and recent items in the user profile and
their influence on deciding which item to recommend next. Experiments on four
real-world recommender system datasets show that the proposed model
significantly outperforms all state-of-the-art models in the task of item
recommendation and achieving improvements of up to 53% in Normalized Discounted
Cumulative Gain (NDCG) and Hit-Ratio. Results also show that CARCA outperformed
several state-of-the-art dedicated image-based recommender systems by merely
utilizing image attributes extracted from a pre-trained ResNet50 in a black-box
fashion.