---
layout: publication
title: Modeling Multi-turn Conversation With Deep Utterance Aggregation
authors: Zhuosheng Zhang, Jiangtong Li, Pengfei Zhu, Hai Zhao, Gongshen Liu
conference: COLING 2018 pages 3740-3752
year: 2018
bibkey: zhang2018modeling
citations: 157
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1806.09102'}]
tags: ["COLING"]
short_authors: Zhang et al.
---
Multi-turn conversation understanding is a major challenge for building
intelligent dialogue systems. This work focuses on retrieval-based response
matching for multi-turn conversation whose related work simply concatenates the
conversation utterances, ignoring the interactions among previous utterances
for context modeling. In this paper, we formulate previous utterances into
context using a proposed deep utterance aggregation model to form a
fine-grained context representation. In detail, a self-matching attention is
first introduced to route the vital information in each utterance. Then the
model matches a response with each refined utterance and the final matching
score is obtained after attentive turns aggregation. Experimental results show
our model outperforms the state-of-the-art methods on three multi-turn
conversation benchmarks, including a newly introduced e-commerce dialogue
corpus.