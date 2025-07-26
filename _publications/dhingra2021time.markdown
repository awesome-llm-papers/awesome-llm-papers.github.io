---
layout: publication
title: Time-aware Language Models As Temporal Knowledge Bases
authors: Bhuwan Dhingra, Jeremy R. Cole, Julian Martin Eisenschlos, Daniel Gillick,
  Jacob Eisenstein, William W. Cohen
conference: Transactions of the Association for Computational Linguistics
year: 2022
bibkey: dhingra2021time
citations: 98
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2106.15110'}]
tags: ["TACL"]
short_authors: Dhingra et al.
---
Many facts come with an expiration date, from the name of the President to
the basketball team Lebron James plays for. But language models (LMs) are
trained on snapshots of data collected at a specific moment in time, and this
can limit their utility, especially in the closed-book setting where the
pretraining corpus must contain the facts the model should memorize. We
introduce a diagnostic dataset aimed at probing LMs for factual knowledge that
changes over time and highlight problems with LMs at either end of the spectrum
-- those trained on specific slices of temporal data, as well as those trained
on a wide range of temporal data. To mitigate these problems, we propose a
simple technique for jointly modeling text with its timestamp. This improves
memorization of seen facts from the training time period, as well as
calibration on predictions about unseen facts from future time periods. We also
show that models trained with temporal context can be efficiently "refreshed"
as new data arrives, without the need for retraining from scratch.