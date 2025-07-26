---
layout: publication
title: Code Structure Guided Transformer For Source Code Summarization
authors: Shuzheng Gao, Cuiyun Gao, Yulan He, Jichuan Zeng, Lun Yiu Nie, Xin Xia, Michael
  R. Lyu
conference: ACM Transactions on Software Engineering and Methodology
year: 2022
bibkey: gao2021code
citations: 72
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.09340'}]
tags: ["Llm For Code", "Model Architecture"]
short_authors: Gao et al.
---
Code summaries help developers comprehend programs and reduce their time to
infer the program functionalities during software maintenance. Recent efforts
resort to deep learning techniques such as sequence-to-sequence models for
generating accurate code summaries, among which Transformer-based approaches
have achieved promising performance. However, effectively integrating the code
structure information into the Transformer is under-explored in this task
domain. In this paper, we propose a novel approach named SG-Trans to
incorporate code structural properties into Transformer. Specifically, we
inject the local symbolic information (e.g., code tokens and statements) and
global syntactic structure (e.g., data flow graph) into the self-attention
module of Transformer as inductive bias. To further capture the hierarchical
characteristics of code, the local information and global structure are
designed to distribute in the attention heads of lower layers and high layers
of Transformer. Extensive evaluation shows the superior performance of SG-Trans
over the state-of-the-art approaches. Compared with the best-performing
baseline, SG-Trans still improves 1.4% and 2.0% in terms of METEOR score, a
metric widely used for measuring generation quality, respectively on two
benchmark datasets.