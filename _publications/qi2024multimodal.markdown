---
layout: publication
title: 'SNIFFER: Multimodal Large Language Model For Explainable Out-of-context Misinformation
  Detection'
authors: Peng Qi, Zehong Yan, Wynne Hsu, Mong Li Lee
conference: Arxiv
year: 2024
citations: 19
bibkey: qi2024multimodal
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2403.03170'}]
tags: [GPT, RAG, Tools, Interpretability and Explainability, Multimodal Models, Model
    Architecture]
---
Misinformation is a prevalent societal issue due to its potential high risks.
Out-of-context (OOC) misinformation, where authentic images are repurposed with
false text, is one of the easiest and most effective ways to mislead audiences.
Current methods focus on assessing image-text consistency but lack convincing
explanations for their judgments, which is essential for debunking
misinformation. While Multimodal Large Language Models (MLLMs) have rich
knowledge and innate capability for visual reasoning and explanation
generation, they still lack sophistication in understanding and discovering the
subtle crossmodal differences. In this paper, we introduce SNIFFER, a novel
multimodal large language model specifically engineered for OOC misinformation
detection and explanation. SNIFFER employs two-stage instruction tuning on
InstructBLIP. The first stage refines the model's concept alignment of generic
objects with news-domain entities and the second stage leverages language-only
GPT-4 generated OOC-specific instruction data to fine-tune the model's
discriminatory powers. Enhanced by external tools and retrieval, SNIFFER not
only detects inconsistencies between text and image but also utilizes external
knowledge for contextual verification. Our experiments show that SNIFFER
surpasses the original MLLM by over 40% and outperforms state-of-the-art
methods in detection accuracy. SNIFFER also provides accurate and persuasive
explanations as validated by quantitative and human evaluations.