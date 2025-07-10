---
layout: publication
title: 'Pmc-llama: Towards Building Open-source Language Models For Medicine'
authors: Chaoyi Wu et al.
conference: Journal of the American Medical Informatics Association
year: 2023
citations: 109
bibkey: wu2023pmc
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2304.14454'}, {name: Code,
    url: 'https://github.com/chaoyi-wu/PMC-LLaMA'}]
tags: [Has Code, Model Architecture, GPT, Fine-Tuning, Applications, Training Techniques,
  Evaluation]
---
Recently, Large Language Models (LLMs) have showcased remarkable capabilities
in natural language understanding. While demonstrating proficiency in everyday
conversations and question-answering situations, these models frequently
struggle in domains that require precision, such as medical applications, due
to their lack of domain-specific knowledge. In this paper, we describe the
procedure for building a powerful, open-source language model specifically
designed for medicine applications, termed as PMC-LLaMA. Our contributions are
threefold: (i) we systematically investigate the process of adapting a
general-purpose foundation language model towards medical domain, this involves
data-centric knowledge injection through the integration of 4.8M biomedical
academic papers and 30K medical textbooks, as well as comprehensive fine-tuning
for alignment with domain-specific instructions; (ii) we contribute a
large-scale, comprehensive dataset for instruction tuning. This dataset
encompasses medical question-answering (QA), rationale for reasoning, and
conversational dialogues, comprising a total of 202M tokens; (iii) we conduct
thorough ablation studies to demonstrate the effectiveness of each proposed
component. While evaluating on various public medical question-answering
benchmarks, our lightweight PMCLLaMA, which consists of only 13 billion
parameters, exhibits superior performance, even surpassing ChatGPT. All models,
codes, datasets can be found in https://github.com/chaoyi-wu/PMC-LLaMA.