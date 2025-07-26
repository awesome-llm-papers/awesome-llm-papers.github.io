---
layout: publication
title: Can Knowledge Editing Really Correct Hallucinations?
authors: Baixiang Huang, Canyu Chen, Xiongxiao Xu, Ali Payani, Kai Shu
conference: No Venue
year: 2024
bibkey: huang2024can
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67171d2d69532dd147c9dba1'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2410.16251'}]
tags: ["Datasets", "Evaluation", "Security"]
short_authors: Huang et al.
---
Large Language Models (LLMs) suffer from hallucinations, referring to the non-factual information in generated content, despite their superior capacities across tasks. Meanwhile, knowledge editing has been developed as a new popular paradigm to correct the erroneous factual knowledge encoded in LLMs with the advantage of avoiding retraining from scratch. However, one common issue of existing evaluation datasets for knowledge editing is that they do not ensure LLMs actually generate hallucinated answers to the evaluation questions before editing. When LLMs are evaluated on such datasets after being edited by different techniques, it is hard to directly adopt the performance to assess the effectiveness of different knowledge editing methods in correcting hallucinations. Thus, the fundamental question remains insufficiently validated: Can knowledge editing really correct hallucinations in LLMs? We proposed HalluEditBench to holistically benchmark knowledge editing methods in correcting real-world hallucinations. First, we rigorously construct a massive hallucination dataset with 9 domains, 26 topics and more than 6,000 hallucinations. Then, we assess the performance of knowledge editing methods in a holistic way on five dimensions including Efficacy, Generalization, Portability, Locality, and Robustness. Through HalluEditBench, we have provided new insights into the potentials and limitations of different knowledge editing methods in correcting hallucinations, which could inspire future improvements and facilitate the progress in the field of knowledge editing.

https://huggingface.co/discussions/paper/67171d2d69532dd147c9dba1