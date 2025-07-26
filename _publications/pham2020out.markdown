---
layout: publication
title: 'Out Of Order: How Important Is The Sequential Order Of Words In A Sentence
  In Natural Language Understanding Tasks?'
authors: Thang M. Pham, Trung Bui, Long Mai, Anh Nguyen
conference: 'Findings of the Association for Computational Linguistics: ACL-IJCNLP
  2021'
year: 2021
bibkey: pham2020out
citations: 68
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.15180'}]
tags: ["Model Architecture"]
short_authors: Pham et al.
---
Do state-of-the-art natural language understanding models care about word
order - one of the most important characteristics of a sequence? Not always! We
found 75% to 90% of the correct predictions of BERT-based classifiers, trained
on many GLUE tasks, remain constant after input words are randomly shuffled.
Despite BERT embeddings are famously contextual, the contribution of each
individual word to downstream tasks is almost unchanged even after the word's
context is shuffled. BERT-based models are able to exploit superficial cues
(e.g. the sentiment of keywords in sentiment analysis; or the word-wise
similarity between sequence-pair inputs in natural language inference) to make
correct decisions when tokens are arranged in random orders. Encouraging
classifiers to capture word order information improves the performance on most
GLUE tasks, SQuAD 2.0 and out-of-samples. Our work suggests that many GLUE
tasks are not challenging machines to understand the meaning of a sentence.