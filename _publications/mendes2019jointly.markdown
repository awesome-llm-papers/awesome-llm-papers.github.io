---
layout: publication
title: Jointly Extracting And Compressing Documents With Summary State Representations
authors: Mendes et al.
conference: Proceedings of the 2019 Conference of the North
year: 2019
bibkey: mendes2019jointly
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.02020'}]
tags: [Training Techniques, Evaluation, Datasets]
---
We present a new neural model for text summarization that first extracts
sentences from a document and then compresses them. The proposed model offers a
balance that sidesteps the difficulties in abstractive methods while generating
more concise summaries than extractive methods. In addition, our model
dynamically determines the length of the output summary based on the gold
summaries it observes during training and does not require length constraints
typical to extractive summarization. The model achieves state-of-the-art
results on the CNN/DailyMail and Newsroom datasets, improving over current
extractive and abstractive methods. Human evaluations demonstrate that our
model generates concise and informative summaries. We also make available a new
dataset of oracle compressive summaries derived automatically from the
CNN/DailyMail reference summaries.