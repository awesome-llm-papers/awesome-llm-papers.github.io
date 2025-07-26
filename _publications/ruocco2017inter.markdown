---
layout: publication
title: Inter-session Modeling For Session-based Recommendation
authors: "Massimiliano Ruocco, Ole Steinar Lillest\xF8l Skrede, Helge Langseth"
conference: Proceedings of the 2nd Workshop on Deep Learning for Recommender Systems
year: 2017
bibkey: ruocco2017inter
citations: 72
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1706.07506'}]
tags: ["Datasets"]
short_authors: "Massimiliano Ruocco, Ole Steinar Lillest\xF8l Skrede, Helge Langseth"
---
In recent years, research has been done on applying Recurrent Neural Networks
(RNNs) as recommender systems. Results have been promising, especially in the
session-based setting where RNNs have been shown to outperform state-of-the-art
models. In many of these experiments, the RNN could potentially improve the
recommendations by utilizing information about the user's past sessions, in
addition to its own interactions in the current session. A problem for
session-based recommendation, is how to produce accurate recommendations at the
start of a session, before the system has learned much about the user's current
interests. We propose a novel approach that extends a RNN recommender to be
able to process the user's recent sessions, in order to improve
recommendations. This is done by using a second RNN to learn from recent
sessions, and predict the user's interest in the current session. By feeding
this information to the original RNN, it is able to improve its
recommendations. Our experiments on two different datasets show that the
proposed approach can significantly improve recommendations throughout the
sessions, compared to a single RNN working only on the current session. The
proposed model especially improves recommendations at the start of sessions,
and is therefore able to deal with the cold start problem within sessions.