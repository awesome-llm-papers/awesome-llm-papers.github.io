---
layout: publication
title: Applying Codebert For Automated Program Repair Of Java Simple Bugs
authors: Mashhadi Ehsan, Hemmati Hadi
conference: 2021 IEEE/ACM 18th International Conference on Mining Software Repositories
  (MSR)
year: 2021
bibkey: mashhadi2021applying
citations: 88
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2103.11626'}]
tags: [Training Techniques, Transformer, BERT, Model Architecture, Datasets, LLM For
    Code]
---
Software debugging, and program repair are among the most time-consuming and
labor-intensive tasks in software engineering that would benefit a lot from
automation. In this paper, we propose a novel automated program repair approach
based on CodeBERT, which is a transformer-based neural architecture pre-trained
on large corpus of source code. We fine-tune our model on the ManySStuBs4J
small and large datasets to automatically generate the fix codes. The results
show that our technique accurately predicts the fixed codes implemented by the
developers in 19-72% of the cases, depending on the type of datasets, in less
than a second per bug. We also observe that our method can generate
varied-length fixes (short and long) and can fix different types of bugs, even
if only a few instances of those types of bugs exist in the training dataset.