---
layout: publication
title: 'NLX-GPT: A Model For Natural Language Explanations In Vision And Vision-language
  Tasks'
authors: Fawaz Sammani, Tanmoy Mukherjee, Nikos Deligiannis
conference: Arxiv
year: 2022
citations: 34
bibkey: sammani2022nlx
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.05081'}, {name: Code,
    url: 'https://github.com/fawazsammani/nlxgpt'}]
tags: [Ethics and Bias, Training Techniques, GPT, Pre-Training, Tools, Interpretability
    and Explainability, Has Code, Security, Multimodal Models, Model Architecture]
---
Natural language explanation (NLE) models aim at explaining the
decision-making process of a black box system via generating natural language
sentences which are human-friendly, high-level and fine-grained. Current NLE
models explain the decision-making process of a vision or vision-language model
(a.k.a., task model), e.g., a VQA model, via a language model (a.k.a.,
explanation model), e.g., GPT. Other than the additional memory resources and
inference time required by the task model, the task and explanation models are
completely independent, which disassociates the explanation from the reasoning
process made to predict the answer. We introduce NLX-GPT, a general, compact
and faithful language model that can simultaneously predict an answer and
explain it. We first conduct pre-training on large scale data of image-caption
pairs for general understanding of images, and then formulate the answer as a
text prediction task along with the explanation. Without region proposals nor a
task model, our resulting overall framework attains better evaluation scores,
contains much less parameters and is 15\\(\times\\) faster than the current SoA
model. We then address the problem of evaluating the explanations which can be
in many times generic, data-biased and can come in several forms. We therefore
design 2 new evaluation measures: (1) explain-predict and (2) retrieval-based
attack, a self-evaluation framework that requires no labels. Code is at:
https://github.com/fawazsammani/nlxgpt.