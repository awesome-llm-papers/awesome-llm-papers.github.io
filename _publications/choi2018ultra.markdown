---
layout: publication
title: Ultra-fine Entity Typing
authors: Eunsol Choi, Omer Levy, Yejin Choi, Luke Zettlemoyer
conference: 'Proceedings of the 56th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2018
bibkey: choi2018ultra
citations: 214
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1807.04905'}]
tags: ["Datasets", "Evaluation"]
short_authors: Choi et al.
---
We introduce a new entity typing task: given a sentence with an entity
mention, the goal is to predict a set of free-form phrases (e.g. skyscraper,
songwriter, or criminal) that describe appropriate types for the target entity.
This formulation allows us to use a new type of distant supervision at large
scale: head words, which indicate the type of the noun phrases they appear in.
We show that these ultra-fine types can be crowd-sourced, and introduce new
evaluation sets that are much more diverse and fine-grained than existing
benchmarks. We present a model that can predict open types, and is trained
using a multitask objective that pools our new head-word supervision with prior
supervision from entity linking. Experimental results demonstrate that our
model is effective in predicting entity types at varying granularity; it
achieves state of the art performance on an existing fine-grained entity typing
benchmark, and sets baselines for our newly-introduced datasets. Our data and
model can be downloaded from: http://nlp.cs.washington.edu/entity_type