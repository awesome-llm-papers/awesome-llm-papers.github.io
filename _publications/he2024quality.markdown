---
layout: publication
title: 'Quality Of Answers Of Generative Large Language Models Vs Peer Patients For
  Interpreting Lab Test Results For Lay Patients: Evaluation Study'
authors: Zhe He et al.
conference: Arxiv
year: 2024
citations: 20
bibkey: he2024quality
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.01693'}]
tags: [GPT, Responsible AI, Tools, BERT, Model Architecture]
---
Lab results are often confusing and hard to understand. Large language models
(LLMs) such as ChatGPT have opened a promising avenue for patients to get their
questions answered. We aim to assess the feasibility of using LLMs to generate
relevant, accurate, helpful, and unharmful responses to lab test-related
questions asked by patients and to identify potential issues that can be
mitigated with augmentation approaches. We first collected lab test results
related question and answer data from Yahoo! Answers and selected 53 QA pairs
for this study. Using the LangChain framework and ChatGPT web portal, we
generated responses to the 53 questions from four LLMs including GPT-4, Meta
LLaMA 2, MedAlpaca, and ORCA_mini. We first assessed the similarity of their
answers using standard QA similarity-based evaluation metrics including ROUGE,
BLEU, METEOR, BERTScore. We also utilized an LLM-based evaluator to judge
whether a target model has higher quality in terms of relevance, correctness,
helpfulness, and safety than the baseline model. Finally, we performed a manual
evaluation with medical experts for all the responses to seven selected
questions on the same four aspects. The results of Win Rate and medical expert
evaluation both showed that GPT-4's responses achieved better scores than all
the other LLM responses and human responses on all four aspects (relevance,
correctness, helpfulness, and safety). However, LLM responses occasionally also
suffer from a lack of interpretation in one's medical context, incorrect
statements, and lack of references. We find that compared to other three LLMs
and human answer from the Q&A website, GPT-4's responses are more accurate,
helpful, relevant, and safer. However, there are cases which GPT-4 responses
are inaccurate and not individualized. We identified a number of ways to
improve the quality of LLM responses.