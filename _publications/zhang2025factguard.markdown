---
layout: publication
title: 'Factguard: Leveraging Multi-agent Systems To Generate Answerable And Unanswerable
  Questions For Enhanced Long-context LLM Extraction'
authors: Zhang et al.
conference: Metametaphysics
year: 2025
bibkey: zhang2025factguard
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2504.05607'}]
tags: [RAG, Training Techniques, Agentic, Tools, Evaluation, Efficiency And Optimization,
  Reinforcement Learning, Datasets]
---
Extractive reading comprehension systems are designed to locate the correct
answer to a question within a given text. However, a persistent challenge lies
in ensuring these models maintain high accuracy in answering questions while
reliably recognizing unanswerable queries. Despite significant advances in
large language models (LLMs) for reading comprehension, this issue remains
critical, particularly as the length of supported contexts continues to expand.
To address this challenge, we propose an innovative data augmentation
methodology grounded in a multi-agent collaborative framework. Unlike
traditional methods, such as the costly human annotation process required for
datasets like SQuAD 2.0, our method autonomously generates evidence-based
question-answer pairs and systematically constructs unanswerable questions.
Using this methodology, we developed the FactGuard-Bench dataset, which
comprises 25,220 examples of both answerable and unanswerable question
scenarios, with context lengths ranging from 8K to 128K. Experimental
evaluations conducted on seven popular LLMs reveal that even the most advanced
models achieve only 61.79% overall accuracy. Furthermore, we emphasize the
importance of a model's ability to reason about unanswerable questions to avoid
generating plausible but incorrect answers. By implementing efficient data
selection and generation within the multi-agent collaborative framework, our
method significantly reduces the traditionally high costs associated with
manual annotation and provides valuable insights for the training and
optimization of LLMs.