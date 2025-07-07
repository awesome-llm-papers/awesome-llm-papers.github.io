---
layout: publication
title: 'Openmedlm: Prompt Engineering Can Out-perform Fine-tuning In Medical Question-answering
  With Open-source Large Language Models'
authors: Jenish Maharjan et al.
conference: Arxiv
year: 2024
citations: 22
bibkey: maharjan2024prompt
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.19371'}]
tags: [Ethics and Bias, Training Techniques, RAG, Few-Shot, Tools, Fine-Tuning, Applications,
  Prompting]
---
LLMs have become increasingly capable at accomplishing a range of
specialized-tasks and can be utilized to expand equitable access to medical
knowledge. Most medical LLMs have involved extensive fine-tuning, leveraging
specialized medical data and significant, thus costly, amounts of computational
power. Many of the top performing LLMs are proprietary and their access is
limited to very few research groups. However, open-source (OS) models represent
a key area of growth for medical LLMs due to significant improvements in
performance and an inherent ability to provide the transparency and compliance
required in healthcare. We present OpenMedLM, a prompting platform which
delivers state-of-the-art (SOTA) performance for OS LLMs on medical benchmarks.
We evaluated a range of OS foundation LLMs (7B-70B) on four medical benchmarks
(MedQA, MedMCQA, PubMedQA, MMLU medical-subset). We employed a series of
prompting strategies, including zero-shot, few-shot, chain-of-thought (random
selection and kNN selection), and ensemble/self-consistency voting. We found
that OpenMedLM delivers OS SOTA results on three common medical LLM benchmarks,
surpassing the previous best performing OS models that leveraged
computationally costly extensive fine-tuning. The model delivers a 72.6%
accuracy on the MedQA benchmark, outperforming the previous SOTA by 2.4%, and
achieves 81.7% accuracy on the MMLU medical-subset, establishing itself as the
first OS LLM to surpass 80% accuracy on this benchmark. Our results highlight
medical-specific emergent properties in OS LLMs which have not yet been
documented to date elsewhere, and showcase the benefits of further leveraging
prompt engineering to improve the performance of accessible LLMs for medical
applications.