---
layout: publication
title: 'Clinical Camel: An Open Expert-level Medical Language Model With Dialogue-based
  Knowledge Encoding'
authors: Augustin Toma et al.
conference: Arxiv
year: 2023
citations: 24
bibkey: toma2023clinical
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.12031'}]
tags: [Ethics and Bias, Training Techniques, GPT, RAG, Fine-Tuning, Responsible AI,
  Applications, Model Architecture]
---
We present Clinical Camel, an open large language model (LLM) explicitly
tailored for clinical research. Fine-tuned from LLaMA-2 using QLoRA, Clinical
Camel achieves state-of-the-art performance across medical benchmarks among
openly available medical LLMs. Leveraging efficient single-GPU training,
Clinical Camel surpasses GPT-3.5 in five-shot evaluations on all assessed
benchmarks, including 64.3% on the USMLE Sample Exam (compared to 58.5% for
GPT-3.5), 77.9% on PubMedQA (compared to 60.2%), 60.7% on MedQA (compared to
53.6%), and 54.2% on MedMCQA (compared to 51.0%). In addition to these
benchmarks, Clinical Camel demonstrates its broader capabilities, such as
synthesizing plausible clinical notes. This work introduces dialogue-based
knowledge encoding, a novel method to synthesize conversational data from dense
medical texts. While benchmark results are encouraging, extensive and rigorous
human evaluation across diverse clinical scenarios is imperative to ascertain
safety before implementation. By openly sharing Clinical Camel, we hope to
foster transparent and collaborative research, working towards the safe
integration of LLMs within the healthcare domain. Significant challenges
concerning reliability, bias, and the potential for outdated knowledge persist.
Nonetheless, the transparency provided by an open approach reinforces the
scientific rigor essential for future clinical applications.