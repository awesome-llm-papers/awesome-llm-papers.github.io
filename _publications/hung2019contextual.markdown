---
layout: publication
title: Contextual Translation Embedding For Visual Relationship Detection And Scene
  Graph Generation
authors: Hung Zih-siou, Mallya Arun, Lazebnik Svetlana
conference: IEEE Transactions on Pattern Analysis and Machine Intelligence
year: 2019
bibkey: hung2019contextual
citations: 73
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1905.11624'}]
tags: [Datasets, LLM for Code, Evaluation]
---
Relations amongst entities play a central role in image understanding. Due to
the complexity of modeling (subject, predicate, object) relation triplets, it
is crucial to develop a method that can not only recognize seen relations, but
also generalize to unseen cases. Inspired by a previously proposed visual
translation embedding model, or VTransE, we propose a context-augmented
translation embedding model that can capture both common and rare relations.
The previous VTransE model maps entities and predicates into a low-dimensional
embedding vector space where the predicate is interpreted as a translation
vector between the embedded features of the bounding box regions of the subject
and the object. Our model additionally incorporates the contextual information
captured by the bounding box of the union of the subject and the object, and
learns the embeddings guided by the constraint predicate \\(\approx\\) union
(subject, object) \\(-\\) subject \\(-\\) object. In a comprehensive evaluation on
multiple challenging benchmarks, our approach outperforms previous
translation-based models and comes close to or exceeds the state of the art
across a range of settings, from small-scale to large-scale datasets, from
common to previously unseen relations. It also achieves promising results for
the recently introduced task of scene graph generation.