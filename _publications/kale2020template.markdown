---
layout: publication
title: Template Guided Text Generation For Task-oriented Dialogue
authors: Mihir Kale, Abhinav Rastogi
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
citations: 19
bibkey: kale2020template
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.15006'}]
tags: [Language Modeling, Reinforcement Learning, Tools, Efficiency and Optimization,
  Evaluation]
---
Virtual assistants such as Google Assistant, Amazon Alexa, and Apple Siri
enable users to interact with a large number of services and APIs on the web
using natural language. In this work, we investigate two methods for Natural
Language Generation (NLG) using a single domain-independent model across a
large number of APIs. First, we propose a schema-guided approach which
conditions the generation on a schema describing the API in natural language.
Our second method investigates the use of a small number of templates, growing
linearly in number of slots, to convey the semantics of the API. To generate
utterances for an arbitrary slot combination, a few simple templates are first
concatenated to give a semantically correct, but possibly incoherent and
ungrammatical utterance. A pre-trained language model is subsequently employed
to rewrite it into coherent, natural sounding text. Through automatic metrics
and human evaluation, we show that our method improves over strong baselines,
is robust to out-of-domain inputs and shows improved sample efficiency.