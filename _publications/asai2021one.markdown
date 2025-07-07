---
layout: publication
title: One Question Answering Model For Many Languages With Cross-lingual Dense Passage
  Retrieval
authors: Akari Asai, Xinyan Yu, Jungo Kasai, Hannaneh Hajishirzi
conference: Arxiv
year: 2021
citations: 30
bibkey: asai2021one
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2107.11976'}]
tags: [Reinforcement Learning, GPT, Training Techniques]
---
We present Cross-lingual Open-Retrieval Answer Generation (CORA), the first
unified many-to-many question answering (QA) model that can answer questions
across many languages, even for ones without language-specific annotated data
or knowledge sources. We introduce a new dense passage retrieval algorithm that
is trained to retrieve documents across languages for a question. Combined with
a multilingual autoregressive generation model, CORA answers directly in the
target language without any translation or in-language retrieval modules as
used in prior work. We propose an iterative training method that automatically
extends annotated data available only in high-resource languages to
low-resource ones. Our results show that CORA substantially outperforms the
previous state of the art on multilingual open QA benchmarks across 26
languages, 9 of which are unseen during training. Our analyses show the
significance of cross-lingual retrieval and generation in many languages,
particularly under low-resource settings.