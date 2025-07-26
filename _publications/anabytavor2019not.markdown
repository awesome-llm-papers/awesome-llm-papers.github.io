---
layout: publication
title: Not Enough Data? Deep Learning To The Rescue!
authors: Ateret Anaby-tavor, Boaz Carmeli, Esther Goldbraich, Amir Kantor, George
  Kour, Segev Shlomov, Naama Tepper, Naama Zwerdling
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2020
bibkey: anabytavor2019not
citations: 278
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.03118'}]
tags: ["AAAI", "Datasets", "Fine-Tuning", "Training Techniques"]
short_authors: Anaby-tavor et al.
---
Based on recent advances in natural language modeling and those in text
generation capabilities, we propose a novel data augmentation method for text
classification tasks. We use a powerful pre-trained neural network model to
artificially synthesize new labeled data for supervised learning. We mainly
focus on cases with scarce labeled data. Our method, referred to as
language-model-based data augmentation (LAMBADA), involves fine-tuning a
state-of-the-art language generator to a specific task through an initial
training phase on the existing (usually small) labeled data. Using the
fine-tuned model and given a class label, new sentences for the class are
generated. Our process then filters these new sentences by using a classifier
trained on the original data. In a series of experiments, we show that LAMBADA
improves classifiers' performance on a variety of datasets. Moreover, LAMBADA
significantly improves upon the state-of-the-art techniques for data
augmentation, specifically those applicable to text classification tasks with
little data.