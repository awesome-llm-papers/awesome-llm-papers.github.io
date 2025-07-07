---
layout: publication
title: 'MEDITRON-70B: Scaling Medical Pretraining For Large Language Models'
authors: Zeming Chen et al.
conference: Arxiv
year: 2023
citations: 54
bibkey: chen2023meditron
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2311.16079'}]
tags: [Training Techniques, Model Architecture, GPT]
---
Large language models (LLMs) can potentially democratize access to medical
knowledge. While many efforts have been made to harness and improve LLMs'
medical knowledge and reasoning capacities, the resulting models are either
closed-source (e.g., PaLM, GPT-4) or limited in scale (<= 13B parameters),
which restricts their abilities. In this work, we improve access to large-scale
medical LLMs by releasing MEDITRON: a suite of open-source LLMs with 7B and 70B
parameters adapted to the medical domain. MEDITRON builds on Llama-2 (through
our adaptation of Nvidia's Megatron-LM distributed trainer), and extends
pretraining on a comprehensively curated medical corpus, including selected
PubMed articles, abstracts, and internationally-recognized medical guidelines.
Evaluations using four major medical benchmarks show significant performance
gains over several state-of-the-art baselines before and after task-specific
finetuning. Overall, MEDITRON achieves a 6% absolute performance gain over the
best public baseline in its parameter class and 3% over the strongest baseline
we finetuned from Llama-2. Compared to closed-source LLMs, MEDITRON-70B
outperforms GPT-3.5 and Med-PaLM and is within 5% of GPT-4 and 10% of
Med-PaLM-2. We release our code for curating the medical pretraining corpus and
the MEDITRON model weights to drive open-source development of more capable
medical LLMs.