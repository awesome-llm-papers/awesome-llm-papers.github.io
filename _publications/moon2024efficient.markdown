---
layout: publication
title: Efficient And Scalable Estimation Of Tool Representations In Vector Space
authors: Moon et al.
conference: Journal of Innovations in Engineering Education
year: 2024
bibkey: moon2024efficient
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2409.02141'}]
tags: [RAG, Training Techniques, Alt, Prompting, Tools, Applications, Fine Tuning,
  Datasets]
---
Recent advancements in function calling and tool use have significantly
enhanced the capabilities of large language models (LLMs) by enabling them to
interact with external information sources and execute complex tasks. However,
the limited context window of LLMs presents challenges when a large number of
tools are available, necessitating efficient methods to manage prompt length
and maintain accuracy. Existing approaches, such as fine-tuning LLMs or
leveraging their reasoning capabilities, either require frequent retraining or
incur significant latency overhead. A more efficient solution involves training
smaller models to retrieve the most relevant tools for a given query, although
this requires high quality, domain-specific data. To address those challenges,
we present a novel framework for generating synthetic data for tool retrieval
applications and an efficient data-driven tool retrieval strategy using small
encoder models. Empowered by LLMs, we create ToolBank, a new tool retrieval
dataset that reflects real human user usages. For tool retrieval methodologies,
we propose novel approaches: (1) Tool2Vec: usage-driven tool embedding
generation for tool retrieval, (2) ToolRefiner: a staged retrieval method that
iteratively improves the quality of retrieved tools, and (3) MLC: framing tool
retrieval as a multi-label classification problem. With these new methods, we
achieve improvements of up to 27.28 in Recall@K on the ToolBench dataset and
30.5 in Recall@K on ToolBank. Additionally, we present further experimental
results to rigorously validate our methods. Our code is available at
https://github.com/SqueezeAILab/Tool2Vec