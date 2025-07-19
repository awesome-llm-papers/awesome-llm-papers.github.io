---
layout: publication
title: 'Sentiprompt: Sentiment Knowledge Enhanced Prompt-tuning For Aspect-based Sentiment
  Analysis'
authors: Li et al.
conference: Arxiv
year: 2021
bibkey: li2021sentiprompt
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.08306'}]
tags: [Prompting, Tools, Merging]
---
Aspect-based sentiment analysis (ABSA) is an emerging fine-grained sentiment
analysis task that aims to extract aspects, classify corresponding sentiment
polarities and find opinions as the causes of sentiment. The latest research
tends to solve the ABSA task in a unified way with end-to-end frameworks. Yet,
these frameworks get fine-tuned from downstream tasks without any task-adaptive
modification. Specifically, they do not use task-related knowledge well or
explicitly model relations between aspect and opinion terms, hindering them
from better performance. In this paper, we propose SentiPrompt to use sentiment
knowledge enhanced prompts to tune the language model in the unified framework.
We inject sentiment knowledge regarding aspects, opinions, and polarities into
prompt and explicitly model term relations via constructing consistency and
polarity judgment templates from the ground truth triplets. Experimental
results demonstrate that our approach can outperform strong baselines on
Triplet Extraction, Pair Extraction, and Aspect Term Extraction with Sentiment
Classification by a notable margin.