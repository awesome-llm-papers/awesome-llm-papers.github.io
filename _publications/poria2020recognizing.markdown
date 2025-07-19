---
layout: publication
title: Recognizing Emotion Cause In Conversations
authors: Poria et al.
conference: Cognitive Computation
year: 2020
bibkey: poria2020recognizing
citations: 89
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.11820'}]
tags: [Interpretability And Explainability, RAG, BERT, Transformer, Model Architecture,
  Reinforcement Learning, Datasets]
---
We address the problem of recognizing emotion cause in conversations, define
two novel sub-tasks of this problem, and provide a corresponding dialogue-level
dataset, along with strong Transformer-based baselines. The dataset is
available at https://github.com/declare-lab/RECCON.
  Introduction: Recognizing the cause behind emotions in text is a fundamental
yet under-explored area of research in NLP. Advances in this area hold the
potential to improve interpretability and performance in affect-based models.
Identifying emotion causes at the utterance level in conversations is
particularly challenging due to the intermingling dynamics among the
interlocutors.
  Method: We introduce the task of Recognizing Emotion Cause in CONversations
with an accompanying dataset named RECCON, containing over 1,000 dialogues and
10,000 utterance cause-effect pairs. Furthermore, we define different cause
types based on the source of the causes, and establish strong Transformer-based
baselines to address two different sub-tasks on this dataset: causal span
extraction and causal emotion entailment.
  Result: Our Transformer-based baselines, which leverage contextual
pre-trained embeddings, such as RoBERTa, outperform the state-of-the-art
emotion cause extraction approaches
  Conclusion: We introduce a new task highly relevant for (explainable)
emotion-aware artificial intelligence: recognizing emotion cause in
conversations, provide a new highly challenging publicly available
dialogue-level dataset for this task, and give strong baseline results on this
dataset.