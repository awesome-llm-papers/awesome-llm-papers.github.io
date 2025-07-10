---
layout: publication
title: 'Assessing AI Detectors In Identifying Ai-generated Code: Implications For
  Education'
authors: Wei Hung Pan et al.
conference: 'ICSE-SEET ''24: 46th International Conference on Software Engineering:
  Software Engineering Education and Training'
year: 2024
citations: 22
bibkey: pan2024assessing
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2401.03676'}]
tags: [Reinforcement Learning, GPT, Prompting, Model Architecture]
---
Educators are increasingly concerned about the usage of Large Language Models
(LLMs) such as ChatGPT in programming education, particularly regarding the
potential exploitation of imperfections in Artificial Intelligence Generated
Content (AIGC) Detectors for academic misconduct. In this paper, we present an
empirical study where the LLM is examined for its attempts to bypass detection
by AIGC Detectors. This is achieved by generating code in response to a given
question using different variants. We collected a dataset comprising 5,069
samples, with each sample consisting of a textual description of a coding
problem and its corresponding human-written Python solution codes. These
samples were obtained from various sources, including 80 from Quescol, 3,264
from Kaggle, and 1,725 from LeetCode. From the dataset, we created 13 sets of
code problem variant prompts, which were used to instruct ChatGPT to generate
the outputs. Subsequently, we assessed the performance of five AIGC detectors.
Our results demonstrate that existing AIGC Detectors perform poorly in
distinguishing between human-written code and AI-generated code.