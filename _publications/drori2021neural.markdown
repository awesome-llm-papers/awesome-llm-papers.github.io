---
layout: publication
title: A Neural Network Solves, Explains, And Generates University Math Problems By
  Program Synthesis And Few-shot Learning At Human Level
authors: Drori et al.
conference: Proceedings of the National Academy of Sciences
year: 2021
bibkey: drori2021neural
citations: 60
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2112.15594'}]
tags: [GPT, Prompting, Evaluation, Transformer, Model Architecture, Few Shot, Survey
    Paper, Datasets]
---
We demonstrate that a neural network pre-trained on text and fine-tuned on
code solves mathematics course problems, explains solutions, and generates new
questions at a human level. We automatically synthesize programs using few-shot
learning and OpenAI's Codex transformer and execute them to solve course
problems at 81% automatic accuracy. We curate a new dataset of questions from
MIT's largest mathematics courses (Single Variable and Multivariable Calculus,
Differential Equations, Introduction to Probability and Statistics, Linear
Algebra, and Mathematics for Computer Science) and Columbia University's
Computational Linear Algebra. We solve questions from a MATH dataset (on
Prealgebra, Algebra, Counting and Probability, Intermediate Algebra, Number
Theory, and Precalculus), the latest benchmark of advanced mathematics problems
designed to assess mathematical reasoning. We randomly sample questions and
generate solutions with multiple modalities, including numbers, equations, and
plots. The latest GPT-3 language model pre-trained on text automatically solves
only 18.8% of these university questions using zero-shot learning and 30.8%
using few-shot learning and the most recent chain of thought prompting. In
contrast, program synthesis with few-shot learning using Codex fine-tuned on
code generates programs that automatically solve 81% of these questions. Our
approach improves the previous state-of-the-art automatic solution accuracy on
the benchmark topics from 8.8% to 81.1%. We perform a survey to evaluate the
quality and difficulty of generated questions. This work is the first to
automatically solve university-level mathematics course questions at a human
level and the first work to explain and generate university-level mathematics
course questions at scale, a milestone for higher education.