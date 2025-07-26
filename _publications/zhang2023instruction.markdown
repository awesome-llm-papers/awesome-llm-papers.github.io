---
layout: publication
title: 'Instruction Tuning For Large Language Models: A Survey'
authors: Shengyu Zhang, Linfeng Dong, Xiaoya Li, Sen Zhang, Xiaofei Sun, Shuhe Wang,
  Jiwei Li, Runyi Hu, Tianwei Zhang, Fei Wu, Guoyin Wang
conference: Arxiv
year: 2023
bibkey: zhang2023instruction
citations: 70
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2308.10792'}]
tags: ["Applications", "Fine-Tuning", "Survey Paper", "Training Techniques"]
short_authors: Zhang et al.
---
This paper surveys research works in the quickly advancing field of
instruction tuning (IT), which can also be referred to as supervised
fine-tuning (SFT)\footnote\{In this paper, unless specified otherwise,
supervised fine-tuning (SFT) and instruction tuning (IT) are used
interchangeably.\}, a crucial technique to enhance the capabilities and
controllability of large language models (LLMs). Instruction tuning refers to
the process of further training LLMs on a dataset consisting of
\textsc\{(instruction, output)\} pairs in a supervised fashion, which bridges the
gap between the next-word prediction objective of LLMs and the users' objective
of having LLMs adhere to human instructions. In this work, we make a systematic
review of the literature, including the general methodology of SFT, the
construction of SFT datasets, the training of SFT models, and applications to
different modalities, domains and application, along with analysis on aspects
that influence the outcome of SFT (e.g., generation of instruction outputs,
size of the instruction dataset, etc). We also review the potential pitfalls of
SFT along with criticism against it, along with efforts pointing out current
deficiencies of existing strategies and suggest some avenues for fruitful
research. Project Page: github.com/xiaoya-li/Instruction-Tuning-Survey