---
layout: publication
title: Automated Quality Assessment Of Cognitive Behavioral Therapy Sessions Through
  Highly Contextualized Language Representations
authors: Nikolaos Flemotomos et al.
conference: PLOS ONE
year: 2021
citations: 20
bibkey: flemotomos2021automated
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2102.11573'}]
tags: [Model Architecture, Interpretability and Explainability, Reinforcement Learning,
  BERT, Evaluation]
---
During a psychotherapy session, the counselor typically adopts techniques
which are codified along specific dimensions (e.g., 'displays warmth and
confidence', or 'attempts to set up collaboration') to facilitate the
evaluation of the session. Those constructs, traditionally scored by trained
human raters, reflect the complex nature of psychotherapy and highly depend on
the context of the interaction. Recent advances in deep contextualized language
models offer an avenue for accurate in-domain linguistic representations which
can lead to robust recognition and scoring of such psychotherapy-relevant
behavioral constructs, and support quality assurance and supervision. In this
work, we propose a BERT-based model for automatic behavioral scoring of a
specific type of psychotherapy, called Cognitive Behavioral Therapy (CBT),
where prior work is limited to frequency-based language features and/or short
text excerpts which do not capture the unique elements involved in a
spontaneous long conversational interaction. The model focuses on the
classification of therapy sessions with respect to the overall score achieved
on the widely-used Cognitive Therapy Rating Scale (CTRS), but is trained in a
multi-task manner in order to achieve higher interpretability. BERT-based
representations are further augmented with available therapy metadata,
providing relevant non-linguistic context and leading to consistent performance
improvements. We train and evaluate our models on a set of 1,118 real-world
therapy sessions, recorded and automatically transcribed. Our best model
achieves an F1 score equal to 72.61% on the binary classification task of low
vs. high total CTRS.