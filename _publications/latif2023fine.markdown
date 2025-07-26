---
layout: publication
title: Fine-tuning Chatgpt For Automatic Scoring
authors: Ehsan Latif, Xiaoming Zhai
conference: 'Computers and Education: Artificial Intelligence'
year: 2024
bibkey: latif2023fine
citations: 73
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.10072'}]
tags: ["Fine-Tuning", "Training Techniques"]
short_authors: Ehsan Latif, Xiaoming Zhai
---
This study highlights the potential of fine-tuned ChatGPT (GPT-3.5) for
automatically scoring student written constructed responses using example
assessment tasks in science education. Recent studies on OpenAI's generative
model GPT-3.5 proved its superiority in predicting the natural language with
high accuracy and human-like responses. GPT-3.5 has been trained over enormous
online language materials such as journals and Wikipedia; therefore, more than
direct usage of pre-trained GPT-3.5 is required for automatic scoring as
students utilize a different language than trained material. These imply that a
domain-specific model, fine-tuned over data for specific tasks, can enhance
model performance. In this study, we fine-tuned GPT-3.5 on six assessment tasks
with a diverse dataset of middle-school and high-school student responses and
expert scoring. The six tasks comprise two multi-label and four multi-class
assessment tasks. We compare the performance of fine-tuned GPT-3.5 with the
fine-tuned state-of-the-art Google's generated language model, BERT. The
results show that in-domain training corpora constructed from science questions
and responses for BERT achieved average accuracy = 0.838, SD = 0.069. GPT-3.5
shows a remarkable average increase (9.1%) in automatic scoring accuracy (mean
= 9.15, SD = 0.042) for the six tasks, p =0.001 < 0.05. Specifically, for
multi-label tasks (item 1 with 5 labels; item 2 with 10 labels), GPT-3.5
achieved significantly higher scoring accuracy than BERT across all the labels,
with the second item achieving a 7.1% increase. The average scoring increase
for the four multi-class items for GPT-3.5 was 10.6% compared to BERT. Our
study confirmed the effectiveness of fine-tuned GPT-3.5 for automatic scoring
of student responses on domain-specific data in education with high accuracy.
We have released fine-tuned models for public use and community engagement.