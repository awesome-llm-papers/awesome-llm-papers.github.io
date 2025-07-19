---
layout: publication
title: Multi-domain Dialogue State Tracking As Dynamic Knowledge Graph Enhanced Question
  Answering
authors: Zhou Li, Small Kevin
conference: Arxiv
year: 2019
bibkey: zhou2019multi
citations: 59
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.06192'}]
tags: [Fine Tuning, Datasets]
---
Multi-domain dialogue state tracking (DST) is a critical component for
conversational AI systems. The domain ontology (i.e., specification of domains,
slots, and values) of a conversational AI system is generally incomplete,
making the capability for DST models to generalize to new slots, values, and
domains during inference imperative. In this paper, we propose to model
multi-domain DST as a question answering problem, referred to as Dialogue State
Tracking via Question Answering (DSTQA). Within DSTQA, each turn generates a
question asking for the value of a (domain, slot) pair, thus making it
naturally extensible to unseen domains, slots, and values. Additionally, we use
a dynamically-evolving knowledge graph to explicitly learn relationships
between (domain, slot) pairs. Our model has a 5.80% and 12.21% relative
improvement over the current state-of-the-art model on MultiWOZ 2.0 and
MultiWOZ 2.1 datasets, respectively. Additionally, our model consistently
outperforms the state-of-the-art model in domain adaptation settings. (Code is
released at https://github.com/alexa/dstqa )