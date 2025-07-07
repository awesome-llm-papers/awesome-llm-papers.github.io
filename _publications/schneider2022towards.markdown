---
layout: publication
title: Towards Trustworthy Autograding Of Short, Multi-lingual, Multi-type Answers
authors: Johannes Schneider, Robin Richner, Micha Riser
conference: Arxiv
year: 2022
citations: 26
bibkey: schneider2022towards
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2201.03425'}]
tags: [Fine-Tuning, Training Techniques, Transformer, Model Architecture]
---
Autograding short textual answers has become much more feasible due to the
rise of NLP and the increased availability of question-answer pairs brought
about by a shift to online education. Autograding performance is still inferior
to human grading. The statistical and black-box nature of state-of-the-art
machine learning models makes them untrustworthy, raising ethical concerns and
limiting their practical utility. Furthermore, the evaluation of autograding is
typically confined to small, monolingual datasets for a specific question type.
This study uses a large dataset consisting of about 10 million question-answer
pairs from multiple languages covering diverse fields such as math and
language, and strong variation in question and answer syntax. We demonstrate
the effectiveness of fine-tuning transformer models for autograding for such
complex datasets. Our best hyperparameter-tuned model yields an accuracy of
about 86.5%, comparable to the state-of-the-art models that are less general
and more tuned to a specific type of question, subject, and language. More
importantly, we address trust and ethical concerns. By involving humans in the
autograding process, we show how to improve the accuracy of automatically
graded answers, achieving accuracy equivalent to that of teaching assistants.
We also show how teachers can effectively control the type of errors made by
the system and how they can validate efficiently that the autograder's
performance on individual exams is close to the expected performance.