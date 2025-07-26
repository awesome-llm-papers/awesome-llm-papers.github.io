---
layout: publication
title: 'RAG Foundry: A Framework For Enhancing Llms For Retrieval Augmented Generation'
authors: Daniel Fleischer, Moshe Berchansky, Moshe Wasserblat, Peter Izsak
conference: No Venue
year: 2024
bibkey: fleischer2024rag
additional_links: [{name: Code, url: 'https://github.com/IntelLabs/RAGFoundry'}, {
    name: Code, url: 'https://huggingface.co/discussions/paper/66b1ddaa8b1fc211c927e88c'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2408.02545'}]
tags: ["Applications", "Has Code", "RAG", "Tools"]
short_authors: Fleischer et al.
---
Implementing Retrieval-Augmented Generation (RAG) systems is inherently complex, requiring deep understanding of data, use cases, and intricate design decisions. Additionally, evaluating these systems presents significant challenges, necessitating assessment of both retrieval accuracy and generative quality through a multi-faceted approach. We introduce RAG Foundry, an open-source framework for augmenting large language models for RAG use cases. RAG Foundry integrates data creation, training, inference and evaluation into a single workflow, facilitating the creation of data-augmented datasets for training and evaluating large language models in RAG settings. This integration enables rapid prototyping and experimentation with various RAG techniques, allowing users to easily generate datasets and train RAG models using internal or specialized knowledge sources. We demonstrate the framework effectiveness by augmenting and fine-tuning Llama-3 and Phi-3 models with diverse RAG configurations, showcasing consistent improvements across three knowledge-intensive datasets. Code is released as open-source in https://github.com/IntelLabs/RAGFoundry.

https://huggingface.co/discussions/paper/66b1ddaa8b1fc211c927e88c