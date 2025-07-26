---
layout: publication
title: 'Chatqa: Building GPT-4 Level Conversational QA Models'
authors: Zihan Liu, Wei Ping, Rajarshi Roy, Peng Xu, Mohammad Shoeybi, Bryan Catanzaro
conference: No Venue
year: 2024
bibkey: liu2024chatqa
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2401.10225'}]
tags: ["Model Architecture"]
short_authors: Liu et al.
---
In this work, we introduce ChatQA, a family of conversational question answering (QA) models, that obtain GPT-4 level accuracies. Specifically, we propose a two-stage instruction tuning method that can significantly improve the zero-shot conversational QA results from large language models (LLMs). To handle retrieval in conversational QA, we fine-tune a dense retriever on a multi-turn QA dataset, which provides comparable results to using the state-of-the-art query rewriting model while largely reducing deployment cost. Notably, our ChatQA-70B can outperform GPT-4 in terms of average score on 10 conversational QA datasets (54.14 vs. 53.90), without relying on any synthetic data from OpenAI GPT models.

https://huggingface.co/discussions/paper/65a9dc6e2ed95c799fe027b5