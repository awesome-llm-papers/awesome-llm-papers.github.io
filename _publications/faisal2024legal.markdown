---
layout: publication
title: 'LEGAL-UQA: A Low-resource Urdu-english Dataset For Legal Question Answering'
authors: Faisal Faizan, Yousaf Umair
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2024
bibkey: faisal2024legal
citations: 68
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.13013'}]
tags: [GPT, Model Architecture, Reinforcement Learning, Applications, AAAI, Datasets]
---
We present LEGAL-UQA, the first Urdu legal question-answering dataset derived
from Pakistan's constitution. This parallel English-Urdu dataset includes 619
question-answer pairs, each with corresponding legal article contexts,
addressing the need for domain-specific NLP resources in low-resource
languages. We describe the dataset creation process, including OCR extraction,
manual refinement, and GPT-4-assisted translation and generation of QA pairs.
Our experiments evaluate the latest generalist language and embedding models on
LEGAL-UQA, with Claude-3.5-Sonnet achieving 99.19% human-evaluated accuracy. We
fine-tune mt5-large-UQA-1.0, highlighting the challenges of adapting
multilingual models to specialized domains. Additionally, we assess retrieval
performance, finding OpenAI's text-embedding-3-large outperforms Mistral's
mistral-embed. LEGAL-UQA bridges the gap between global NLP advancements and
localized applications, particularly in constitutional law, and lays the
foundation for improved legal information access in Pakistan.