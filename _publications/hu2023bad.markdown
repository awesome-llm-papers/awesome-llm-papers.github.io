---
layout: publication
title: 'Bad Actor, Good Advisor: Exploring The Role Of Large Language Models In Fake
  News Detection'
authors: Beizhe Hu et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2023
citations: 54
bibkey: hu2023bad
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2309.12247'}]
tags: [Model Architecture, Distillation, GPT, Reinforcement Learning, Efficiency and
    Optimization, BERT]
---
Detecting fake news requires both a delicate sense of diverse clues and a
profound understanding of the real-world background, which remains challenging
for detectors based on small language models (SLMs) due to their knowledge and
capability limitations. Recent advances in large language models (LLMs) have
shown remarkable performance in various tasks, but whether and how LLMs could
help with fake news detection remains underexplored. In this paper, we
investigate the potential of LLMs in fake news detection. First, we conduct an
empirical study and find that a sophisticated LLM such as GPT 3.5 could
generally expose fake news and provide desirable multi-perspective rationales
but still underperforms the basic SLM, fine-tuned BERT. Our subsequent analysis
attributes such a gap to the LLM's inability to select and integrate rationales
properly to conclude. Based on these findings, we propose that current LLMs may
not substitute fine-tuned SLMs in fake news detection but can be a good advisor
for SLMs by providing multi-perspective instructive rationales. To instantiate
this proposal, we design an adaptive rationale guidance network for fake news
detection (ARG), in which SLMs selectively acquire insights on news analysis
from the LLMs' rationales. We further derive a rationale-free version of ARG by
distillation, namely ARG-D, which services cost-sensitive scenarios without
querying LLMs. Experiments on two real-world datasets demonstrate that ARG and
ARG-D outperform three types of baseline methods, including SLM-based,
LLM-based, and combinations of small and large language models.