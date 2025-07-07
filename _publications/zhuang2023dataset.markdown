---
layout: publication
title: 'Toolqa: A Dataset For LLM Question Answering With External Tools'
authors: Yuchen Zhuang, Yue Yu, Kuan Wang, Haotian Sun, Chao Zhang
conference: Arxiv
year: 2023
citations: 24
bibkey: zhuang2023dataset
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2306.13304'}]
tags: [Pre-Training, Training Techniques, Tools, Reinforcement Learning]
---
Large Language Models (LLMs) have demonstrated impressive performance in
various NLP tasks, but they still suffer from challenges such as hallucination
and weak numerical reasoning. To overcome these challenges, external tools can
be used to enhance LLMs' question-answering abilities. However, current
evaluation methods do not distinguish between questions that can be answered
using LLMs' internal knowledge and those that require external information
through tool use. To address this issue, we introduce a new dataset called
ToolQA, which is designed to faithfully evaluate LLMs' ability to use external
tools for question answering. Our development of ToolQA involved a scalable,
automated process for dataset curation, along with 13 specialized tools
designed for interaction with external knowledge in order to answer questions.
Importantly, we strive to minimize the overlap between our benchmark data and
LLMs' pre-training data, enabling a more precise evaluation of LLMs' tool-use
reasoning abilities. We conducted an in-depth diagnosis of existing tool-use
LLMs to highlight their strengths, weaknesses, and potential improvements. Our
findings set a new benchmark for evaluating LLMs and suggest new directions for
future advancements. Our data and code are freely available to the broader
scientific community on GitHub.