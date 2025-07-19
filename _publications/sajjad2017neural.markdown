---
layout: publication
title: Neural Machine Translation Training In A Multi-domain Scenario
authors: Sajjad et al.
conference: Proceedings of the 14th International Workshop on Spoken Language Translation
  (IWSLT) 2017
year: 2017
bibkey: sajjad2017neural
citations: 54
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1708.08712'}]
tags: [Fine Tuning, Alt, Training Techniques, SLT]
---
In this paper, we explore alternative ways to train a neural machine
translation system in a multi-domain scenario. We investigate data
concatenation (with fine tuning), model stacking (multi-level fine tuning),
data selection and multi-model ensemble. Our findings show that the best
translation quality can be achieved by building an initial system on a
concatenation of available out-of-domain data and then fine-tuning it on
in-domain data. Model stacking works best when training begins with the
furthest out-of-domain data and the model is incrementally fine-tuned with the
next furthest domain and so on. Data selection did not give the best results,
but can be considered as a decent compromise between training time and
translation quality. A weighted ensemble of different individual models
performed better than data selection. It is beneficial in a scenario when there
is no time for fine-tuning an already trained model.