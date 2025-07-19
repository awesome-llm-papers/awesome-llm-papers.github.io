---
layout: publication
title: Exploring The Potential Of Large Language Models (llms) In Learning On Graphs
authors: Chen et al.
conference: ACM SIGKDD Explorations Newsletter
year: 2023
bibkey: chen2023exploring
citations: 65
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2307.03393'}]
tags: [Model Architecture, KDD, Fine Tuning, Fine-Tuning, Applications, RAG, Datasets,
  Reinforcement Learning, Attention Mechanism]
---
Learning on Graphs has attracted immense attention due to its wide real-world
applications. The most popular pipeline for learning on graphs with textual
node attributes primarily relies on Graph Neural Networks (GNNs), and utilizes
shallow text embedding as initial node representations, which has limitations
in general knowledge and profound semantic understanding. In recent years,
Large Language Models (LLMs) have been proven to possess extensive common
knowledge and powerful semantic comprehension abilities that have
revolutionized existing workflows to handle text data. In this paper, we aim to
explore the potential of LLMs in graph machine learning, especially the node
classification task, and investigate two possible pipelines: LLMs-as-Enhancers
and LLMs-as-Predictors. The former leverages LLMs to enhance nodes' text
attributes with their massive knowledge and then generate predictions through
GNNs. The latter attempts to directly employ LLMs as standalone predictors. We
conduct comprehensive and systematical studies on these two pipelines under
various settings. From comprehensive empirical results, we make original
observations and find new insights that open new possibilities and suggest
promising directions to leverage LLMs for learning on graphs. Our codes and
datasets are available at https://github.com/CurryTang/Graph-LLM.