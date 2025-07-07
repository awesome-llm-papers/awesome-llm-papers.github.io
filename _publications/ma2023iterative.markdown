---
layout: publication
title: An Iterative Optimizing Framework For Radiology Report Summarization With Chatgpt
authors: Chong Ma et al.
conference: IEEE Transactions on Artificial Intelligence (Early Access)(12 February
  2024)
year: 2023
citations: 27
bibkey: ma2023iterative
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2304.08448'}]
tags: [Training Techniques, GPT, RAG, Pre-Training, Tools, Fine-Tuning, In-Context
    Learning, Efficiency and Optimization, Prompting, Model Architecture]
---
The 'Impression' section of a radiology report is a critical basis for
communication between radiologists and other physicians, and it is typically
written by radiologists based on the 'Findings' section. However, writing
numerous impressions can be laborious and error-prone for radiologists.
Although recent studies have achieved promising results in automatic impression
generation using large-scale medical text data for pre-training and fine-tuning
pre-trained language models, such models often require substantial amounts of
medical text data and have poor generalization performance. While large
language models (LLMs) like ChatGPT have shown strong generalization
capabilities and performance, their performance in specific domains, such as
radiology, remains under-investigated and potentially limited. To address this
limitation, we propose ImpressionGPT, which leverages the in-context learning
capability of LLMs by constructing dynamic contexts using domain-specific,
individualized data. This dynamic prompt approach enables the model to learn
contextual knowledge from semantically similar examples from existing data.
Additionally, we design an iterative optimization algorithm that performs
automatic evaluation on the generated impression results and composes the
corresponding instruction prompts to further optimize the model. The proposed
ImpressionGPT model achieves state-of-the-art performance on both MIMIC-CXR and
OpenI datasets without requiring additional training data or fine-tuning the
LLMs. This work presents a paradigm for localizing LLMs that can be applied in
a wide range of similar application scenarios, bridging the gap between
general-purpose LLMs and the specific language processing needs of various
domains.