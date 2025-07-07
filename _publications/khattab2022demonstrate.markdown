---
layout: publication
title: 'Demonstrate-search-predict: Composing Retrieval And Language Models For Knowledge-intensive
  NLP'
authors: Omar Khattab et al.
conference: Arxiv
year: 2022
citations: 41
bibkey: khattab2022demonstrate
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.14024'}, {name: Code,
    url: 'https://github.com/stanfordnlp/dsp'}]
tags: [GPT, RAG, Tools, Reinforcement Learning, In-Context Learning, Has Code, Prompting,
  Model Architecture]
---
Retrieval-augmented in-context learning has emerged as a powerful approach
for addressing knowledge-intensive tasks using frozen language models (LM) and
retrieval models (RM). Existing work has combined these in simple
"retrieve-then-read" pipelines in which the RM retrieves passages that are
inserted into the LM prompt. To begin to fully realize the potential of frozen
LMs and RMs, we propose Demonstrate-Search-Predict (DSP), a framework that
relies on passing natural language texts in sophisticated pipelines between an
LM and an RM. DSP can express high-level programs that bootstrap pipeline-aware
demonstrations, search for relevant passages, and generate grounded
predictions, systematically breaking down problems into small transformations
that the LM and RM can handle more reliably. We have written novel DSP programs
for answering questions in open-domain, multi-hop, and conversational settings,
establishing in early evaluations new state-of-the-art in-context learning
results and delivering 37-120%, 8-39%, and 80-290% relative gains against the
vanilla LM (GPT-3.5), a standard retrieve-then-read pipeline, and a
contemporaneous self-ask pipeline, respectively. We release DSP at
https://github.com/stanfordnlp/dsp