---
layout: publication
title: 'RAG Vs Fine-tuning: Pipelines, Tradeoffs, And A Case Study On Agriculture'
authors: Angels Balaguer et al.
conference: Arxiv
year: 2024
citations: 20
bibkey: balaguer2024rag
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2401.08406'}]
tags: [Model Architecture, GPT, Fine-Tuning, RAG, Applications, Prompting, Training
    Techniques, Evaluation]
---
There are two common ways in which developers are incorporating proprietary
and domain-specific data when building applications of Large Language Models
(LLMs): Retrieval-Augmented Generation (RAG) and Fine-Tuning. RAG augments the
prompt with the external data, while fine-Tuning incorporates the additional
knowledge into the model itself. However, the pros and cons of both approaches
are not well understood. In this paper, we propose a pipeline for fine-tuning
and RAG, and present the tradeoffs of both for multiple popular LLMs, including
Llama2-13B, GPT-3.5, and GPT-4. Our pipeline consists of multiple stages,
including extracting information from PDFs, generating questions and answers,
using them for fine-tuning, and leveraging GPT-4 for evaluating the results. We
propose metrics to assess the performance of different stages of the RAG and
fine-Tuning pipeline. We conduct an in-depth study on an agricultural dataset.
Agriculture as an industry has not seen much penetration of AI, and we study a
potentially disruptive application - what if we could provide location-specific
insights to a farmer? Our results show the effectiveness of our dataset
generation pipeline in capturing geographic-specific knowledge, and the
quantitative and qualitative benefits of RAG and fine-tuning. We see an
accuracy increase of over 6 p.p. when fine-tuning the model and this is
cumulative with RAG, which increases accuracy by 5 p.p. further. In one
particular experiment, we also demonstrate that the fine-tuned model leverages
information from across geographies to answer specific questions, increasing
answer similarity from 47% to 72%. Overall, the results point to how systems
built using LLMs can be adapted to respond and incorporate knowledge across a
dimension that is critical for a specific industry, paving the way for further
applications of LLMs in other industrial domains.