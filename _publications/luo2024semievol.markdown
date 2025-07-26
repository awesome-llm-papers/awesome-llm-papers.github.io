---
layout: publication
title: 'Semievol: Semi-supervised Fine-tuning For LLM Adaptation'
authors: Junyu Luo, Xiao Luo, Xiusi Chen, Zhiping Xiao, Wei Ju, Ming Zhang
conference: No Venue
year: 2024
bibkey: luo2024semievol
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2410.14745'}]
tags: ["Fine-Tuning", "Training Techniques"]
short_authors: Luo et al.
---
Supervised fine-tuning (SFT) is crucial in adapting large language models (LLMs) to a specific domain or task. However, only a limited amount of labeled data is available in practical applications, which poses a severe challenge for SFT in yielding satisfactory results. Therefore, a data-efficient framework that can fully exploit labeled and unlabeled data for LLM fine-tuning is highly anticipated. Towards this end, we introduce a semi-supervised fine-tuning framework named SemiEvol for LLM adaptation from a propagate-and-select manner. For knowledge propagation, SemiEvol adopts a bi-level approach, propagating knowledge from labeled data to unlabeled data through both in-weight and in-context methods. For knowledge selection, SemiEvol incorporates a collaborative learning mechanism, selecting higher-quality pseudo-response samples. We conducted experiments using GPT-4o-mini and Llama-3.1 on seven general or domain-specific datasets, demonstrating significant improvements in model performance on target data. Furthermore, we compared SemiEvol with SFT and self-evolution methods, highlighting its practicality in hybrid data scenarios.

https://huggingface.co/discussions/paper/671701ff9ec0ff4d1501fad0