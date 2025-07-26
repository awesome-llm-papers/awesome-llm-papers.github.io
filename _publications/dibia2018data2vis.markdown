---
layout: publication
title: 'Data2vis: Automatic Generation Of Data Visualizations Using Sequence To Sequence
  Recurrent Neural Networks'
authors: "Victor Dibia, \xC7a\u011Fatay Demiralp"
conference: IEEE Computer Graphics and Applications
year: 2019
bibkey: dibia2018data2vis
citations: 158
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1804.03126'}]
tags: ["Applications", "Model Architecture", "Tools"]
short_authors: "Victor Dibia, \xC7a\u011Fatay Demiralp"
---
Rapidly creating effective visualizations using expressive grammars is
challenging for users who have limited time and limited skills in statistics
and data visualization. Even high-level, dedicated visualization tools often
require users to manually select among data attributes, decide which
transformations to apply, and specify mappings between visual encoding
variables and raw or transformed attributes.
  In this paper we introduce Data2Vis, a neural translation model for
automatically generating visualizations from given datasets. We formulate
visualization generation as a sequence to sequence translation problem where
data specifications are mapped to visualization specifications in a declarative
language (Vega-Lite). To this end, we train a multilayered attention-based
recurrent neural network (RNN) with long short-term memory (LSTM) units on a
corpus of visualization specifications.
  Qualitative results show that our model learns the vocabulary and syntax for
a valid visualization specification, appropriate transformations (count, bins,
mean) and how to use common data selection patterns that occur within data
visualizations. Data2Vis generates visualizations that are comparable to
manually-created visualizations in a fraction of the time, with potential to
learn more complex visualization strategies at scale.