---
layout: publication
title: Extractive Summarization Via Chatgpt For Faithful Summary Generation
authors: Haopeng Zhang, Xiao Liu, Jiawei Zhang
conference: Arxiv
year: 2023
citations: 31
bibkey: zhang2023extractive
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2304.04193'}]
tags: [Fine-Tuning, Training Techniques, Model Architecture, GPT]
---
Extractive summarization is a crucial task in natural language processing
that aims to condense long documents into shorter versions by directly
extracting sentences. The recent introduction of large language models has
attracted significant interest in the NLP community due to its remarkable
performance on a wide range of downstream tasks. This paper first presents a
thorough evaluation of ChatGPT's performance on extractive summarization and
compares it with traditional fine-tuning methods on various benchmark datasets.
Our experimental analysis reveals that ChatGPT exhibits inferior extractive
summarization performance in terms of ROUGE scores compared to existing
supervised systems, while achieving higher performance based on LLM-based
evaluation metrics. In addition, we explore the effectiveness of in-context
learning and chain-of-thought reasoning for enhancing its performance.
Furthermore, we find that applying an extract-then-generate pipeline with
ChatGPT yields significant performance improvements over abstractive baselines
in terms of summary faithfulness. These observations highlight potential
directions for enhancing ChatGPT's capabilities in faithful summarization using
two-stage approaches.