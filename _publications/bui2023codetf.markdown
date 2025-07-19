---
layout: publication
title: 'Codetf: One-stop Transformer Library For State-of-the-art Code LLM'
authors: Bui et al.
conference: Nature Communications
year: 2023
bibkey: bui2023codetf
citations: 120
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2306.00029'}]
tags: [RAG, Tools, Evaluation, Transformer, Model Architecture, Reinforcement Learning,
  Datasets, LLM For Code]
---
Code intelligence plays a key role in transforming modern software
engineering. Recently, deep learning-based models, especially Transformer-based
large language models (LLMs), have demonstrated remarkable potential in
tackling these tasks by leveraging massive open-source code data and
programming language features. However, the development and deployment of such
models often require expertise in both machine learning and software
engineering, creating a barrier for the model adoption. In this paper, we
present CodeTF, an open-source Transformer-based library for state-of-the-art
Code LLMs and code intelligence. Following the principles of modular design and
extensible framework, we design CodeTF with a unified interface to enable rapid
access and development across different types of models, datasets and tasks.
Our library supports a collection of pretrained Code LLM models and popular
code benchmarks, including a standardized interface to train and serve code
LLMs efficiently, and data features such as language-specific parsers and
utility functions for extracting code attributes. In this paper, we describe
the design principles, the architecture, key modules and components, and
compare with other related library tools. Finally, we hope CodeTF is able to
bridge the gap between machine learning/generative AI and software engineering,
providing a comprehensive open-source solution for developers, researchers, and
practitioners.