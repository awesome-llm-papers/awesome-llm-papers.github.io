---
layout: publication
title: Data Augmentation For Intent Classification With Off-the-shelf Large Language
  Models
authors: Gaurav Sahu et al.
conference: Proceedings of the 4th Workshop on NLP for Conversational AI
year: 2022
citations: 28
bibkey: sahu2022data
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2204.01959'}]
tags: [Model Architecture, GPT, Fine-Tuning, Few-Shot, Prompting, Training Techniques]
---
Data augmentation is a widely employed technique to alleviate the problem of
data scarcity. In this work, we propose a prompting-based approach to generate
labelled training data for intent classification with off-the-shelf language
models (LMs) such as GPT-3. An advantage of this method is that no
task-specific LM-fine-tuning for data generation is required; hence the method
requires no hyper-parameter tuning and is applicable even when the available
training data is very scarce. We evaluate the proposed method in a few-shot
setting on four diverse intent classification tasks. We find that GPT-generated
data significantly boosts the performance of intent classifiers when intents in
consideration are sufficiently distinct from each other. In tasks with
semantically close intents, we observe that the generated data is less helpful.
Our analysis shows that this is because GPT often generates utterances that
belong to a closely-related intent instead of the desired one. We present
preliminary evidence that a prompting-based GPT classifier could be helpful in
filtering the generated data to enhance its quality.