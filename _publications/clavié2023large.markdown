---
layout: publication
title: 'Large Language Models In The Workplace: A Case Study On Prompt Engineering
  For Job Type Classification'
authors: "Benjamin Clavi\xE9, Alexandru Ciceu, Frederick Naylor, Guillaume Souli\xE9\
  , Thomas Brightwell"
conference: Lecture Notes in Computer Science
year: 2023
citations: 32
bibkey: "clavi\xE92023large"
additional_links: [{name: Paper, url: 'http://arxiv.org/abs/2303.07142v3'}]
tags: [Model Architecture, GPT, Few-Shot, Reinforcement Learning, Prompting, BERT]
---
This case study investigates the task of job classification in a real-world
setting, where the goal is to determine whether an English-language job posting
is appropriate for a graduate or entry-level position. We explore multiple
approaches to text classification, including supervised approaches such as
traditional models like Support Vector Machines (SVMs) and state-of-the-art
deep learning methods such as DeBERTa. We compare them with Large Language
Models (LLMs) used in both few-shot and zero-shot classification settings. To
accomplish this task, we employ prompt engineering, a technique that involves
designing prompts to guide the LLMs towards the desired output. Specifically,
we evaluate the performance of two commercially available state-of-the-art
GPT-3.5-based language models, text-davinci-003 and gpt-3.5-turbo. We also
conduct a detailed analysis of the impact of different aspects of prompt
engineering on the model's performance. Our results show that, with a
well-designed prompt, a zero-shot gpt-3.5-turbo classifier outperforms all
other models, achieving a 6% increase in Precision@95% Recall compared to the
best supervised approach. Furthermore, we observe that the wording of the
prompt is a critical factor in eliciting the appropriate "reasoning" in the
model, and that seemingly minor aspects of the prompt significantly affect the
model's performance.