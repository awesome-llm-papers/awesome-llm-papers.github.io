---
layout: publication
title: 'Chatgpt: Jack Of All Trades, Master Of None'
authors: "Jan Koco\u0144 et al."
conference: Information Fusion
year: 2023
citations: 392
bibkey: "koco\u01442023jack"
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2302.10724'}]
tags: [Model Architecture, Ethics and Bias, Transformer, RAG, Few-Shot, Prompting,
  GPT, Evaluation]
---
OpenAI has released the Chat Generative Pre-trained Transformer (ChatGPT) and
revolutionized the approach in artificial intelligence to human-model
interaction. Several publications on ChatGPT evaluation test its effectiveness
on well-known natural language processing (NLP) tasks. However, the existing
studies are mostly non-automated and tested on a very limited scale. In this
work, we examined ChatGPT's capabilities on 25 diverse analytical NLP tasks,
most of them subjective even to humans, such as sentiment analysis, emotion
recognition, offensiveness, and stance detection. In contrast, the other tasks
require more objective reasoning like word sense disambiguation, linguistic
acceptability, and question answering. We also evaluated GPT-4 model on five
selected subsets of NLP tasks. We automated ChatGPT and GPT-4 prompting process
and analyzed more than 49k responses. Our comparison of its results with
available State-of-the-Art (SOTA) solutions showed that the average loss in
quality of the ChatGPT model was about 25% for zero-shot and few-shot
evaluation. For GPT-4 model, a loss for semantic tasks is significantly lower
than for ChatGPT. We showed that the more difficult the task (lower SOTA
performance), the higher the ChatGPT loss. It especially refers to pragmatic
NLP problems like emotion recognition. We also tested the ability to
personalize ChatGPT responses for selected subjective tasks via Random
Contextual Few-Shot Personalization, and we obtained significantly better
user-based predictions. Additional qualitative analysis revealed a ChatGPT
bias, most likely due to the rules imposed on human trainers by OpenAI. Our
results provide the basis for a fundamental discussion of whether the high
quality of recent predictive NLP models can indicate a tool's usefulness to
society and how the learning and validation procedures for such systems should
be established.