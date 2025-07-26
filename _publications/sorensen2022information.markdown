---
layout: publication
title: An Information-theoretic Approach To Prompt Engineering Without Ground Truth
  Labels
authors: Taylor Sorensen, Joshua Robinson, Christopher Michael Rytting, Alexander
  Glenn Shaw, Kyle Jeffrey Rogers, Alexia Pauline Delorey, Mahmoud Khalil, Nancy Fulda,
  David Wingate
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
bibkey: sorensen2022information
citations: 81
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.11364'}]
tags: ["Prompting"]
short_authors: Sorensen et al.
---
Pre-trained language models derive substantial linguistic and factual
knowledge from the massive corpora on which they are trained, and prompt
engineering seeks to align these models to specific tasks. Unfortunately,
existing prompt engineering methods require significant amounts of labeled
data, access to model parameters, or both. We introduce a new method for
selecting prompt templates \textit\{without labeled examples\} and
\textit\{without direct access to the model\}. Specifically, over a set of
candidate templates, we choose the template that maximizes the mutual
information between the input and the corresponding model output. Across 8
datasets representing 7 distinct NLP tasks, we show that when a template has
high mutual information, it also has high accuracy on the task. On the largest
model, selecting prompts with our method gets 90% of the way from the average
prompt accuracy to the best prompt accuracy and requires no ground truth
labels.