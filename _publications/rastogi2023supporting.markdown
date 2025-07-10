---
layout: publication
title: Supporting Human-ai Collaboration In Auditing Llms With Llms
authors: Charvi Rastogi, Marco Tulio Ribeiro, Nicholas King, Harsha Nori, Saleema
  Amershi
conference: 'AIES ''23: AAAI/ACM Conference on AI, Ethics, and Society'
year: 2023
citations: 38
bibkey: rastogi2023supporting
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2304.09991'}]
tags: [Model Architecture, Ethics and Bias, RAG, Tools, Reinforcement Learning, GPT]
---
Large language models are becoming increasingly pervasive and ubiquitous in
society via deployment in sociotechnical systems. Yet these language models, be
it for classification or generation, have been shown to be biased and behave
irresponsibly, causing harm to people at scale. It is crucial to audit these
language models rigorously. Existing auditing tools leverage either or both
humans and AI to find failures. In this work, we draw upon literature in
human-AI collaboration and sensemaking, and conduct interviews with research
experts in safe and fair AI, to build upon the auditing tool: AdaTest (Ribeiro
and Lundberg, 2022), which is powered by a generative large language model
(LLM). Through the design process we highlight the importance of sensemaking
and human-AI communication to leverage complementary strengths of humans and
generative models in collaborative auditing. To evaluate the effectiveness of
the augmented tool, AdaTest++, we conduct user studies with participants
auditing two commercial language models: OpenAI's GPT-3 and Azure's sentiment
analysis model. Qualitative analysis shows that AdaTest++ effectively leverages
human strengths such as schematization, hypothesis formation and testing.
Further, with our tool, participants identified a variety of failures modes,
covering 26 different topics over 2 tasks, that have been shown before in
formal audits and also those previously under-reported.