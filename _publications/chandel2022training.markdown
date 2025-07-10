---
layout: publication
title: Training And Evaluating A Jupyter Notebook Data Science Assistant
authors: Shubham Chandel, Colin B. Clement, Guillermo Serrato, Neel Sundaresan
conference: Arxiv
year: 2022
citations: 16
bibkey: chandel2022training
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2201.12901'}]
tags: [Model Architecture, Transformer, RAG, Training Techniques, Evaluation]
---
We study the feasibility of a Data Science assistant powered by a
sequence-to-sequence transformer by training a new model JuPyT5 on all publicly
available Jupyter Notebook GitHub repositories and developing a new metric:
Data Science Problems (DSP). DSP is a collection of 1119 problems curated from
306 pedagogical notebooks with 92 dataset dependencies, natural language and
Markdown problem descriptions, and assert-based unit tests. These notebooks
were designed to test university students' mastery of various Python
implementations of Math and Data Science, and we now leverage them to study the
ability of JuPyT5 to understand and pass the tests. We analyze the content of
DSP, validate its quality, and we find that given 100 sampling attempts JuPyT5
is able to solve 77.5% of the DSP problems. We further present various
ablation and statistical analyses and compare DSP to other recent natural
language to code benchmarks.