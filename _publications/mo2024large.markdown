---
layout: publication
title: Large Language Model (LLM) AI Text Generation Detection Based On Transformer
  Deep Learning Algorithm
authors: Yuhong Mo, Hao Qin, Yushan Dong, Ziyi Zhu, Zhenglin Li
conference: Arxiv
year: 2024
citations: 19
bibkey: mo2024large
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2405.06652'}]
tags: [Language Modeling, Model Architecture, Transformer, Training Techniques, Evaluation,
  Merging]
---
In this paper, a tool for detecting LLM AI text generation is developed based
on the Transformer model, aiming to improve the accuracy of AI text generation
detection and provide reference for subsequent research. Firstly the text is
Unicode normalised, converted to lowercase form, characters other than
non-alphabetic characters and punctuation marks are removed by regular
expressions, spaces are added around punctuation marks, first and last spaces
are removed, consecutive ellipses are replaced with single spaces and the text
is connected using the specified delimiter. Next remove non-alphabetic
characters and extra whitespace characters, replace multiple consecutive
whitespace characters with a single space and again convert to lowercase form.
The deep learning model combines layers such as LSTM, Transformer and CNN for
text classification or sequence labelling tasks. The training and validation
sets show that the model loss decreases from 0.127 to 0.005 and accuracy
increases from 94.96 to 99.8, indicating that the model has good detection and
classification ability for AI generated text. The test set confusion matrix and
accuracy show that the model has 99% prediction accuracy for AI-generated text,
with a precision of 0.99, a recall of 1, and an f1 score of 0.99, achieving a
very high classification accuracy. Looking forward, it has the prospect of wide
application in the field of AI text detection.