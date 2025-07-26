---
layout: publication
title: Studying The Usage Of Text-to-text Transfer Transformer To Support Code-related
  Tasks
authors: Antonio Mastropaolo, Simone Scalabrino, Nathan Cooper, David Nader Palacio,
  Denys Poshyvanyk, Rocco Oliveto, Gabriele Bavota
conference: 2021 IEEE/ACM 43rd International Conference on Software Engineering (ICSE)
year: 2021
bibkey: mastropaolo2021studying
citations: 181
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2102.02017'}]
tags: ["Llm For Code", "Model Architecture"]
short_authors: Mastropaolo et al.
---
Deep learning (DL) techniques are gaining more and more attention in the
software engineering community. They have been used to support several
code-related tasks, such as automatic bug fixing and code comments generation.
Recent studies in the Natural Language Processing (NLP) field have shown that
the Text-To-Text Transfer Transformer (T5) architecture can achieve
state-of-the-art performance for a variety of NLP tasks. The basic idea behind
T5 is to first pre-train a model on a large and generic dataset using a
self-supervised task ( e.g: filling masked words in sentences). Once the model
is pre-trained, it is fine-tuned on smaller and specialized datasets, each one
related to a specific task ( e.g: language translation, sentence
classification). In this paper, we empirically investigate how the T5 model
performs when pre-trained and fine-tuned to support code-related tasks. We
pre-train a T5 model on a dataset composed of natural language English text and
source code. Then, we fine-tune such a model by reusing datasets used in four
previous works that used DL techniques to: (i) fix bugs, (ii) inject code
mutants, (iii) generate assert statements, and (iv) generate code comments. We
compared the performance of this single model with the results reported in the
four original papers proposing DL-based solutions for those four tasks. We show
that our T5 model, exploiting additional data for the self-supervised
pre-training phase, can achieve performance improvements over the four
baselines.