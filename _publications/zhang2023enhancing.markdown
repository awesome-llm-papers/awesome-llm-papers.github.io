---
layout: publication
title: Enhancing Financial Sentiment Analysis Via Retrieval Augmented Large Language
  Models
authors: Zhang et al.
conference: 4th ACM International Conference on AI in Finance
year: 2023
bibkey: zhang2023enhancing
citations: 84
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.04027'}]
tags: [RAG, Training Techniques, GPT, Tools, Evaluation, Model Architecture, Datasets]
---
Financial sentiment analysis is critical for valuation and investment
decision-making. Traditional NLP models, however, are limited by their
parameter size and the scope of their training datasets, which hampers their
generalization capabilities and effectiveness in this field. Recently, Large
Language Models (LLMs) pre-trained on extensive corpora have demonstrated
superior performance across various NLP tasks due to their commendable
zero-shot abilities. Yet, directly applying LLMs to financial sentiment
analysis presents challenges: The discrepancy between the pre-training
objective of LLMs and predicting the sentiment label can compromise their
predictive performance. Furthermore, the succinct nature of financial news,
often devoid of sufficient context, can significantly diminish the reliability
of LLMs' sentiment analysis. To address these challenges, we introduce a
retrieval-augmented LLMs framework for financial sentiment analysis. This
framework includes an instruction-tuned LLMs module, which ensures LLMs behave
as predictors of sentiment labels, and a retrieval-augmentation module which
retrieves additional context from reliable external sources. Benchmarked
against traditional models and LLMs like ChatGPT and LLaMA, our approach
achieves 15% to 48% performance gain in accuracy and F1 score.