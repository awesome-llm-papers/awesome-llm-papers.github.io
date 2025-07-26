---
layout: publication
title: Re-translation Versus Streaming For Simultaneous Translation
authors: Naveen Arivazhagan, Colin Cherry, Wolfgang Macherey, George Foster
conference: Proceedings of the 17th International Conference on Spoken Language Translation
year: 2020
bibkey: arivazhagan2020re
citations: 61
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.03643'}]
tags: ["Applications"]
short_authors: Arivazhagan et al.
---
There has been great progress in improving streaming machine translation, a
simultaneous paradigm where the system appends to a growing hypothesis as more
source content becomes available. We study a related problem in which revisions
to the hypothesis beyond strictly appending words are permitted. This is
suitable for applications such as live captioning an audio feed. In this
setting, we compare custom streaming approaches to re-translation, a
straightforward strategy where each new source token triggers a distinct
translation from scratch. We find re-translation to be as good or better than
state-of-the-art streaming systems, even when operating under constraints that
allow very few revisions. We attribute much of this success to a previously
proposed data-augmentation technique that adds prefix-pairs to the training
data, which alongside wait-k inference forms a strong baseline for streaming
translation. We also highlight re-translation's ability to wrap arbitrarily
powerful MT systems with an experiment showing large improvements from an
upgrade to its base model.