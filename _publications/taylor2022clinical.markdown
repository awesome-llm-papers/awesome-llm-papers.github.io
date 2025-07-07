---
layout: publication
title: Clinical Prompt Learning With Frozen Language Models
authors: Niall Taylor, Yi Zhang, Dan Joyce, Alejo Nevado-holgado, Andrey Kormilitzin
conference: Arxiv
year: 2022
citations: 18
bibkey: taylor2022clinical
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2205.05535'}, {name: Code,
    url: 'https://github.com/NtaylorOX/Public_Clinical_Prompt'}]
tags: [Training Techniques, GPT, Pre-Training, Few-Shot, Fine-Tuning, Has Code, Prompting,
  Model Architecture]
---
Prompt learning is a new paradigm in the Natural Language Processing (NLP)
field which has shown impressive performance on a number of natural language
tasks with common benchmarking text datasets in full, few-shot, and zero-shot
train-evaluation setups. Recently, it has even been observed that large but
frozen pre-trained language models (PLMs) with prompt learning outperform
smaller but fine-tuned models. However, as with many recent NLP trends, the
performance of even the largest PLMs such as GPT-3 do not perform well on
specialized domains (e.g. medical text), and the common practice to achieve
State of the Art (SoTA) results still consists of pre-training and fine-tuning
the PLMs on downstream tasks. The reliance on fine-tuning large PLMs is
problematic in clinical settings where data is often held in non-GPU
environments, and more resource efficient methods of training specialized
domain models is crucial. We investigated the viability of prompt learning on
clinically meaningful decision tasks and directly compared with more
traditional fine-tuning methods. Results are partially in line with the prompt
learning literature, with prompt learning able to match or improve on
traditional fine-tuning with substantially fewer trainable parameters and
requiring less training data. We argue that prompt learning therefore provides
lower computational resource costs applicable to clinical settings, that can
serve as an alternative to fine-tuning ever increasing in size PLMs.
Complementary code to reproduce experiments presented in this work can be found
at: https://github.com/NtaylorOX/Public_Clinical_Prompt.