---
layout: publication
title: Interacting Attention-gated Recurrent Networks For Recommendation
authors: Pei et al.
conference: Proceedings of the 2017 ACM on Conference on Information and Knowledge
  Management
year: 2017
bibkey: pei2017interacting
citations: 57
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1709.01532'}]
tags: [Attention Mechanism, Tools, Model Architecture, CIKM, Reinforcement Learning,
  Datasets]
---
Capturing the temporal dynamics of user preferences over items is important
for recommendation. Existing methods mainly assume that all time steps in
user-item interaction history are equally relevant to recommendation, which
however does not apply in real-world scenarios where user-item interactions can
often happen accidentally. More importantly, they learn user and item dynamics
separately, thus failing to capture their joint effects on user-item
interactions. To better model user and item dynamics, we present the
Interacting Attention-gated Recurrent Network (IARN) which adopts the attention
model to measure the relevance of each time step. In particular, we propose a
novel attention scheme to learn the attention scores of user and item history
in an interacting way, thus to account for the dependencies between user and
item dynamics in shaping user-item interactions. By doing so, IARN can
selectively memorize different time steps of a user's history when predicting
her preferences over different items. Our model can therefore provide
meaningful interpretations for recommendation results, which could be further
enhanced by auxiliary features. Extensive validation on real-world datasets
shows that IARN consistently outperforms state-of-the-art methods.