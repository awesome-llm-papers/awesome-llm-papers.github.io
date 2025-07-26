---
layout: publication
title: Towards Efficient And Effective Adaptation Of Large Language Models For Sequential
  Recommendation
authors: Bo Peng, Ben Burns, Ziqi Chen, Srinivasan Parthasarathy, Xia Ning
conference: SSRN Electronic Journal
year: 2023
bibkey: peng2023towards
citations: 76
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.01612'}]
tags: ["Efficiency", "Training Techniques"]
short_authors: Peng et al.
---
In recent years, with large language models (LLMs) achieving state-of-the-art
performance in context understanding, increasing efforts have been dedicated to
developing LLM-enhanced sequential recommendation (SR) methods. Considering
that most existing LLMs are not specifically optimized for recommendation
tasks, adapting them for SR becomes a critical step in LLM-enhanced SR methods.
Though numerous adaptation methods have been developed, it still remains a
significant challenge to adapt LLMs for SR both efficiently and effectively. To
address this challenge, in this paper, we introduce a novel side sequential
network adaptation method, denoted as SSNA, for LLM enhanced SR. SSNA features
three key designs to allow both efficient and effective LLM adaptation. First,
SSNA learns adapters separate from LLMs, while fixing all the pre-trained
parameters within LLMs to allow efficient adaptation. In addition, SSNA adapts
the top-a layers of LLMs jointly, and integrates adapters sequentially for
enhanced effectiveness (i.e., recommendation performance). We compare SSNA
against five state-of-the-art baseline methods on five benchmark datasets using
three LLMs. The experimental results demonstrate that SSNA significantly
outperforms all the baseline methods in terms of recommendation performance,
and achieves substantial improvement over the best-performing baseline methods
at both run-time and memory efficiency during training. Our analysis shows the
effectiveness of integrating adapters in a sequential manner. Our parameter
study demonstrates the effectiveness of jointly adapting the top-a layers of
LLMs.