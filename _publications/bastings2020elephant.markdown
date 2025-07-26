---
layout: publication
title: 'The Elephant In The Interpretability Room: Why Use Attention As Explanation
  When We Have Saliency Methods?'
authors: Jasmijn Bastings, Katja Filippova
conference: Proceedings of the Third BlackboxNLP Workshop on Analyzing and Interpreting
  Neural Networks for NLP
year: 2020
bibkey: bastings2020elephant
citations: 137
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.05607'}]
tags: []
short_authors: Jasmijn Bastings, Katja Filippova
---
There is a recent surge of interest in using attention as explanation of
model predictions, with mixed evidence on whether attention can be used as
such. While attention conveniently gives us one weight per input token and is
easily extracted, it is often unclear toward what goal it is used as
explanation. We find that often that goal, whether explicitly stated or not, is
to find out what input tokens are the most relevant to a prediction, and that
the implied user for the explanation is a model developer. For this goal and
user, we argue that input saliency methods are better suited, and that there
are no compelling reasons to use attention, despite the coincidence that it
provides a weight for each input. With this position paper, we hope to shift
some of the recent focus on attention to saliency methods, and for authors to
clearly state the goal and user for their explanations.