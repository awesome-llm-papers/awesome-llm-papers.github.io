---
layout: publication
title: Can Large Language Models Reason About Medical Questions?
authors: "Valentin Li\xE9vin, Christoffer Egeberg Hother, Andreas Geert Motzfeldt,\
  \ Ole Winther"
conference: Patterns
year: 2024
bibkey: "li\xE9vin2022can"
citations: 135
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2207.08143'}]
tags: ["Datasets", "Few-Shot", "GPT", "Model Architecture", "Prompting"]
short_authors: "Li\xE9vin et al."
---
Although large language models (LLMs) often produce impressive outputs, it
remains unclear how they perform in real-world scenarios requiring strong
reasoning skills and expert domain knowledge. We set out to investigate whether
close- and open-source models (GPT-3.5, LLama-2, etc.) can be applied to answer
and reason about difficult real-world-based questions. We focus on three
popular medical benchmarks (MedQA-USMLE, MedMCQA, and PubMedQA) and multiple
prompting scenarios: Chain-of-Thought (CoT, think step-by-step), few-shot and
retrieval augmentation. Based on an expert annotation of the generated CoTs, we
found that InstructGPT can often read, reason and recall expert knowledge.
Last, by leveraging advances in prompt engineering (few-shot and ensemble
methods), we demonstrated that GPT-3.5 not only yields calibrated predictive
distributions, but also reaches the passing score on three datasets:
MedQA-USMLE 60.2%, MedMCQA 62.7% and PubMedQA 78.2%. Open-source models are
closing the gap: Llama-2 70B also passed the MedQA-USMLE with 62.5% accuracy.