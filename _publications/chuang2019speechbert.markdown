---
layout: publication
title: 'Speechbert: An Audio-and-text Jointly Learned Language Model For End-to-end
  Spoken Question Answering'
authors: Yung-sung Chuang, Chi-liang Liu, Hung-yi Lee, Lin-shan Lee
conference: Interspeech 2020
year: 2020
bibkey: chuang2019speechbert
citations: 78
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1910.11559'}]
tags: ["INTERSPEECH", "Model Architecture"]
short_authors: Chuang et al.
---
While various end-to-end models for spoken language understanding tasks have
been explored recently, this paper is probably the first known attempt to
challenge the very difficult task of end-to-end spoken question answering
(SQA). Learning from the very successful BERT model for various text processing
tasks, here we proposed an audio-and-text jointly learned SpeechBERT model.
This model outperformed the conventional approach of cascading ASR with the
following text question answering (TQA) model on datasets including ASR errors
in answer spans, because the end-to-end model was shown to be able to extract
information out of audio data before ASR produced errors. When ensembling the
proposed end-to-end model with the cascade architecture, even better
performance was achieved. In addition to the potential of end-to-end SQA, the
SpeechBERT can also be considered for many other spoken language understanding
tasks just as BERT for many text processing tasks.