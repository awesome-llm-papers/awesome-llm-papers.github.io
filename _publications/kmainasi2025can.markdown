---
layout: publication
title: Can Large Language Models Predict The Outcome Of Judicial Decisions?
authors: Kmainasi Mohamed Bayan, Shahroor Ali Ezzat, Al-ghraibah Amani
conference: Proceedings of the 47th International ACM SIGIR Conference on Research
  and Development in Information Retrieval
year: 2025
bibkey: kmainasi2025can
citations: 58
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2501.09768'}]
tags: [Training Techniques, Tools, Evaluation, BERT, Model Architecture, Efficiency
    And Optimization, SIGIR, Fine Tuning, Datasets]
---
Large Language Models (LLMs) have shown exceptional capabilities in Natural
Language Processing (NLP) across diverse domains. However, their application in
specialized tasks such as Legal Judgment Prediction (LJP) for low-resource
languages like Arabic remains underexplored. In this work, we address this gap
by developing an Arabic LJP dataset, collected and preprocessed from Saudi
commercial court judgments. We benchmark state-of-the-art open-source LLMs,
including LLaMA-3.2-3B and LLaMA-3.1-8B, under varying configurations such as
zero-shot, one-shot, and fine-tuning using LoRA. Additionally, we employed a
comprehensive evaluation framework that integrates both quantitative metrics
(such as BLEU, ROUGE, and BERT) and qualitative assessments (including
Coherence, Legal Language, Clarity, etc.) using an LLM. Our results demonstrate
that fine-tuned smaller models achieve comparable performance to larger models
in task-specific contexts while offering significant resource efficiency.
Furthermore, we investigate the impact of fine-tuning the model on a diverse
set of instructions, offering valuable insights into the development of a more
human-centric and adaptable LLM. We have made the dataset, code, and models
publicly available to provide a solid foundation for future research in Arabic
legal NLP.