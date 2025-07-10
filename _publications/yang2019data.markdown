---
layout: publication
title: Data Augmentation For BERT Fine-tuning In Open-domain Question Answering
authors: Wei Yang et al.
conference: Arxiv
year: 2019
citations: 42
bibkey: yang2019data
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.06652'}]
tags: [Model Architecture, Fine-Tuning, Training Techniques, BERT, Evaluation]
---
Recently, a simple combination of passage retrieval using off-the-shelf IR
techniques and a BERT reader was found to be very effective for question
answering directly on Wikipedia, yielding a large improvement over the previous
state of the art on a standard benchmark dataset. In this paper, we present a
data augmentation technique using distant supervision that exploits positive as
well as negative examples. We apply a stage-wise approach to fine tuning BERT
on multiple datasets, starting with data that is "furthest" from the test data
and ending with the "closest". Experimental results show large gains in
effectiveness over previous approaches on English QA datasets, and we establish
new baselines on two recent Chinese QA datasets.