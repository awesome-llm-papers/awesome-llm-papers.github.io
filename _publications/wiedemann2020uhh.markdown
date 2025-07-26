---
layout: publication
title: 'UHH-LT At Semeval-2020 Task 12: Fine-tuning Of Pre-trained Transformer Networks
  For Offensive Language Detection'
authors: Gregor Wiedemann, Seid Muhie Yimam, Chris Biemann
conference: Proceedings of the Fourteenth Workshop on Semantic Evaluation
year: 2020
bibkey: wiedemann2020uhh
citations: 65
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.11493'}]
tags: ["Fine-Tuning", "Model Architecture", "Training Techniques"]
short_authors: Gregor Wiedemann, Seid Muhie Yimam, Chris Biemann
---
Fine-tuning of pre-trained transformer networks such as BERT yield
state-of-the-art results for text classification tasks. Typically, fine-tuning
is performed on task-specific training datasets in a supervised manner. One can
also fine-tune in unsupervised manner beforehand by further pre-training the
masked language modeling (MLM) task. Hereby, in-domain data for unsupervised
MLM resembling the actual classification target dataset allows for domain
adaptation of the model. In this paper, we compare current pre-trained
transformer networks with and without MLM fine-tuning on their performance for
offensive language detection. Our MLM fine-tuned RoBERTa-based classifier
officially ranks 1st in the SemEval 2020 Shared Task~12 for the English
language. Further experiments with the ALBERT model even surpass this result.