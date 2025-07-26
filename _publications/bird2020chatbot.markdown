---
layout: publication
title: 'Chatbot Interaction With Artificial Intelligence: Human Data Augmentation
  With T5 And Language Transformer Ensemble For Text Classification'
authors: "Jordan J. Bird, Anik\xF3 Ek\xE1rt, Diego R. Faria"
conference: Journal of Ambient Intelligence and Humanized Computing
year: 2021
bibkey: bird2020chatbot
citations: 61
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.05990'}]
tags: ["Tools"]
short_authors: "Jordan J. Bird, Anik\xF3 Ek\xE1rt, Diego R. Faria"
---
In this work, we present the Chatbot Interaction with Artificial Intelligence
(CI-AI) framework as an approach to the training of deep learning chatbots for
task classification. The intelligent system augments human-sourced data via
artificial paraphrasing in order to generate a large set of training data for
further classical, attention, and language transformation-based learning
approaches for Natural Language Processing. Human beings are asked to
paraphrase commands and questions for task identification for further execution
of a machine. The commands and questions are split into training and validation
sets. A total of 483 responses were recorded. Secondly, the training set is
paraphrased by the T5 model in order to augment it with further data. Seven
state-of-the-art transformer-based text classification algorithms (BERT,
DistilBERT, RoBERTa, DistilRoBERTa, XLM, XLM-RoBERTa, and XLNet) are
benchmarked for both sets after fine-tuning on the training data for two
epochs. We find that all models are improved when training data is augmented by
the T5 model, with an average increase of classification accuracy by 4.01%. The
best result was the RoBERTa model trained on T5 augmented data which achieved
98.96% classification accuracy. Finally, we found that an ensemble of the five
best-performing transformer models via Logistic Regression of output label
predictions led to an accuracy of 99.59% on the dataset of human responses. A
highly-performing model allows the intelligent system to interpret human
commands at the social-interaction level through a chatbot-like interface (e.g.
"Robot, can we have a conversation?") and allows for better accessibility to AI
by non-technical users.