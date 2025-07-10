---
layout: publication
title: 'Chatgraph: Interpretable Text Classification By Converting Chatgpt Knowledge
  To Graphs'
authors: Yucheng Shi et al.
conference: 2023 IEEE International Conference on Data Mining Workshops (ICDMW)
year: 2023
citations: 18
bibkey: shi2023interpretable
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.03513'}]
tags: [Model Architecture, RAG, Applications, Interpretability and Explainability,
  Tools, GPT]
---
ChatGPT, as a recently launched large language model (LLM), has shown
superior performance in various natural language processing (NLP) tasks.
However, two major limitations hinder its potential applications: (1) the
inflexibility of finetuning on downstream tasks and (2) the lack of
interpretability in the decision-making process. To tackle these limitations,
we propose a novel framework that leverages the power of ChatGPT for specific
tasks, such as text classification, while improving its interpretability. The
proposed framework conducts a knowledge graph extraction task to extract
refined and structural knowledge from the raw data using ChatGPT. The rich
knowledge is then converted into a graph, which is further used to train an
interpretable linear classifier to make predictions. To evaluate the
effectiveness of our proposed method, we conduct experiments on four datasets.
The result shows that our method can significantly improve the performance
compared to directly utilizing ChatGPT for text classification tasks. And our
method provides a more transparent decision-making process compared with
previous text classification methods.