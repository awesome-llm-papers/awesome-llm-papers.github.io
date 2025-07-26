---
layout: publication
title: 'KEPLER: A Unified Model For Knowledge Embedding And Pre-trained Language Representation'
authors: Xiaozhi Wang, Tianyu Gao, Zhaocheng Zhu, Zhengyan Zhang, Zhiyuan Liu, Juanzi
  Li, Jian Tang
conference: Transactions of the Association for Computational Linguistics
year: 2021
bibkey: wang2019kepler
citations: 506
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.06136'}]
tags: ["Has Code", "TACL", "Training Techniques"]
short_authors: Wang et al.
---
Pre-trained language representation models (PLMs) cannot well capture factual
knowledge from text. In contrast, knowledge embedding (KE) methods can
effectively represent the relational facts in knowledge graphs (KGs) with
informative entity embeddings, but conventional KE models cannot take full
advantage of the abundant textual information. In this paper, we propose a
unified model for Knowledge Embedding and Pre-trained LanguagE Representation
(KEPLER), which can not only better integrate factual knowledge into PLMs but
also produce effective text-enhanced KE with the strong PLMs. In KEPLER, we
encode textual entity descriptions with a PLM as their embeddings, and then
jointly optimize the KE and language modeling objectives. Experimental results
show that KEPLER achieves state-of-the-art performances on various NLP tasks,
and also works remarkably well as an inductive KE model on KG link prediction.
Furthermore, for pre-training and evaluating KEPLER, we construct Wikidata5M, a
large-scale KG dataset with aligned entity descriptions, and benchmark
state-of-the-art KE methods on it. It shall serve as a new KE benchmark and
facilitate the research on large KG, inductive KE, and KG with text. The source
code can be obtained from https://github.com/THU-KEG/KEPLER.