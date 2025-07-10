---
layout: publication
title: A Simple But Effective Method To Incorporate Multi-turn Context With BERT For
  Conversational Machine Comprehension
authors: Yasuhito Ohsugi, Itsumi Saito, Kyosuke Nishida, Hisako Asano, Junji Tomita
conference: Proceedings of the First Workshop on NLP for Conversational AI
year: 2019
citations: 18
bibkey: ohsugi2019simple
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1905.12848'}]
tags: [Model Architecture, RAG, Pre-Training, Training Techniques, BERT]
---
Conversational machine comprehension (CMC) requires understanding the context
of multi-turn dialogue. Using BERT, a pre-training language model, has been
successful for single-turn machine comprehension, while modeling multiple turns
of question answering with BERT has not been established because BERT has a
limit on the number and the length of input sequences. In this paper, we
propose a simple but effective method with BERT for CMC. Our method uses BERT
to encode a paragraph independently conditioned with each question and each
answer in a multi-turn context. Then, the method predicts an answer on the
basis of the paragraph representations encoded with BERT. The experiments with
representative CMC datasets, QuAC and CoQA, show that our method outperformed
recently published methods (+0.8 F1 on QuAC and +2.1 F1 on CoQA). In addition,
we conducted a detailed analysis of the effects of the number and types of
dialogue history on the accuracy of CMC, and we found that the gold answer
history, which may not be given in an actual conversation, contributed to the
model performance most on both datasets.