---
layout: publication
title: Automatic Spanish Translation Of The Squad Dataset For Multilingual Question
  Answering
authors: "Casimiro Pio Carrino, Marta R. Costa-juss\xE0, Jos\xE9 A. R. Fonollosa"
conference: Arxiv
year: 2019
citations: 40
bibkey: carrino2019automatic
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1912.05200'}]
tags: [Model Architecture, Fine-Tuning, Training Techniques, BERT, Evaluation]
---
Recently, multilingual question answering became a crucial research topic,
and it is receiving increased interest in the NLP community. However, the
unavailability of large-scale datasets makes it challenging to train
multilingual QA systems with performance comparable to the English ones. In
this work, we develop the Translate Align Retrieve (TAR) method to
automatically translate the Stanford Question Answering Dataset (SQuAD) v1.1 to
Spanish. We then used this dataset to train Spanish QA systems by fine-tuning a
Multilingual-BERT model. Finally, we evaluated our QA models with the recently
proposed MLQA and XQuAD benchmarks for cross-lingual Extractive QA.
Experimental results show that our models outperform the previous
Multilingual-BERT baselines achieving the new state-of-the-art value of 68.1 F1
points on the Spanish MLQA corpus and 77.6 F1 and 61.8 Exact Match points on
the Spanish XQuAD corpus. The resulting, synthetically generated SQuAD-es v1.1
corpora, with almost 100% of data contained in the original English version, to
the best of our knowledge, is the first large-scale QA training resource for
Spanish.