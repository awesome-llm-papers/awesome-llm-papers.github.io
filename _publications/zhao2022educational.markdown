---
layout: publication
title: Educational Question Generation Of Children Storybooks Via Question Type Distribution
  Learning And Event-centric Summarization
authors: Zhenjie Zhao et al.
conference: Arxiv
year: 2022
citations: 15
bibkey: zhao2022educational
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.14187'}]
tags: [RAG, Transformer, Model Architecture]
---
Generating educational questions of fairytales or storybooks is vital for
improving children's literacy ability. However, it is challenging to generate
questions that capture the interesting aspects of a fairytale story with
educational meaningfulness. In this paper, we propose a novel question
generation method that first learns the question type distribution of an input
story paragraph, and then summarizes salient events which can be used to
generate high-cognitive-demand questions. To train the event-centric
summarizer, we finetune a pre-trained transformer-based sequence-to-sequence
model using silver samples composed by educational question-answer pairs. On a
newly proposed educational question answering dataset FairytaleQA, we show good
performance of our method on both automatic and human evaluation metrics. Our
work indicates the necessity of decomposing question type distribution learning
and event-centric summary generation for educational question generation.