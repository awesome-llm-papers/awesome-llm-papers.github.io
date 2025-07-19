---
layout: publication
title: 'Biotabqa: Instruction Learning For Biomedical Table Question Answering'
authors: Luo et al.
conference: Computer Methods and Programs in Biomedicine
year: 2022
bibkey: luo2022biotabqa
citations: 110
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2207.02419'}]
tags: [RAG, Training Techniques, Evaluation, Applications, Datasets]
---
Table Question Answering (TQA) is an important but under-explored task. Most
of the existing QA datasets are in unstructured text format and only few of
them use tables as the context. To the best of our knowledge, none of TQA
datasets exist in the biomedical domain where tables are frequently used to
present information. In this paper, we first curate a table question answering
dataset, BioTABQA, using 22 templates and the context from a biomedical
textbook on differential diagnosis. BioTABQA can not only be used to teach a
model how to answer questions from tables but also evaluate how a model
generalizes to unseen questions, an important scenario for biomedical
applications. To achieve the generalization evaluation, we divide the templates
into 17 training and 5 cross-task evaluations. Then, we develop two baselines
using single and multi-tasks learning on BioTABQA. Furthermore, we explore
instructional learning, a recent technique showing impressive generalizing
performance. Experimental results show that our instruction-tuned model
outperforms single and multi-task baselines on an average by ~23% and ~6%
across various evaluation settings, and more importantly, instruction-tuned
model outperforms baselines by ~5% on cross-tasks.