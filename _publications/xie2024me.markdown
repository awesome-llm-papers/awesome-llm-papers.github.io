---
layout: publication
title: 'Me Llama: Foundation Large Language Models For Medical Applications'
authors: Qianqian Xie et al.
conference: Springer Science and Business Media LLC
year: 2024
citations: 16
bibkey: xie2024me
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.12749'}]
tags: [Model Architecture, GPT, Fine-Tuning, RAG, Applications, Pre-Training, Training
    Techniques, Evaluation]
---
Recent advancements in large language models (LLMs) like ChatGPT and LLaMA
show promise in medical applications, yet challenges remain in medical language
comprehension. This study presents Me-LLaMA, a new medical LLM family based on
open-source LLaMA models, optimized for medical text analysis and diagnosis by
leveraging large-scale, domain-specific datasets. The Me-LLaMA family,
including foundation models Me-LLaMA 13/70B and their chat-enhanced versions,
was developed through continued pre-training and instruction tuning with 129B
tokens and 214K samples from biomedical and clinical sources. Training the 70B
models required over 100,000 A100 GPU hours. Me-LLaMA's performance was
evaluated across six medical text analysis tasks using 12 benchmark datasets
and complex clinical case diagnosis, with automatic and human evaluations.
Results indicate Me-LLaMA outperforms LLaMA and other open-source medical LLMs
in zero-shot and supervised settings. Task-specific tuning further boosts
performance, surpassing ChatGPT on 7 of 8 datasets and GPT-4 on 5 of 8. For
complex clinical cases, Me-LLaMA achieves performance comparable to ChatGPT and
GPT-4. This work underscores the importance of domain-specific data in
developing medical LLMs and addresses the high computational costs involved in
training, highlighting a balance between pre-training and fine-tuning
strategies. Me-LLaMA models are now accessible under user agreements, providing
a valuable resource for advancing medical AI.