---
layout: publication
title: What Do Llms Know About Financial Markets? A Case Study On Reddit Market Sentiment
  Analysis
authors: Xiang Deng, Vasilisa Bashlovkina, Feng Han, Simon Baumgartner, Michael Bendersky
conference: Arxiv
year: 2022
citations: 23
bibkey: deng2022what
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.11311'}]
tags: [Distillation, Training Techniques, Efficiency and Optimization, Applications,
  Prompting]
---
Market sentiment analysis on social media content requires knowledge of both
financial markets and social media jargon, which makes it a challenging task
for human raters. The resulting lack of high-quality labeled data stands in the
way of conventional supervised learning methods. Instead, we approach this
problem using semi-supervised learning with a large language model (LLM). Our
pipeline generates weak financial sentiment labels for Reddit posts with an LLM
and then uses that data to train a small model that can be served in
production. We find that prompting the LLM to produce Chain-of-Thought
summaries and forcing it through several reasoning paths helps generate more
stable and accurate labels, while using a regression loss further improves
distillation quality. With only a handful of prompts, the final model performs
on par with existing supervised models. Though production applications of our
model are limited by ethical considerations, the model's competitive
performance points to the great potential of using LLMs for tasks that
otherwise require skill-intensive annotation.