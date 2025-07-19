---
layout: publication
title: 'Gpt3mix: Leveraging Large-scale Language Models For Text Augmentation'
authors: Yoo et al.
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2021'
year: 2021
bibkey: yoo2021gpt3mix
citations: 104
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.08826'}]
tags: [Model Architecture, Prompting, Training Techniques, Fine Tuning, ACL, EMNLP,
  Few Shot, RAG, GPT]
---
Large-scale language models such as GPT-3 are excellent few-shot learners,
allowing them to be controlled via natural text prompts. Recent studies report
that prompt-based direct classification eliminates the need for fine-tuning but
lacks data and inference scalability. This paper proposes a novel data
augmentation technique that leverages large-scale language models to generate
realistic text samples from a mixture of real samples. We also propose
utilizing soft-labels predicted by the language models, effectively distilling
knowledge from the large-scale language models and creating textual
perturbations simultaneously. We perform data augmentation experiments on
diverse classification tasks and show that our method hugely outperforms
existing text augmentation methods. Ablation studies and a qualitative analysis
provide more insights into our approach.