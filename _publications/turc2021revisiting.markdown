---
layout: publication
title: Revisiting The Primacy Of English In Zero-shot Cross-lingual Transfer
authors: Iulia Turc, Kenton Lee, Jacob Eisenstein, Ming-wei Chang, Kristina Toutanova
conference: Arxiv
year: 2021
citations: 34
bibkey: turc2021revisiting
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2106.16171'}]
tags: [Model Architecture, Fine-Tuning, Training Techniques, BERT, Evaluation, Merging]
---
Despite their success, large pre-trained multilingual models have not
completely alleviated the need for labeled data, which is cumbersome to collect
for all target languages. Zero-shot cross-lingual transfer is emerging as a
practical solution: pre-trained models later fine-tuned on one transfer
language exhibit surprising performance when tested on many target languages.
English is the dominant source language for transfer, as reinforced by popular
zero-shot benchmarks. However, this default choice has not been systematically
vetted. In our study, we compare English against other transfer languages for
fine-tuning, on two pre-trained multilingual models (mBERT and mT5) and
multiple classification and question answering tasks. We find that other
high-resource languages such as German and Russian often transfer more
effectively, especially when the set of target languages is diverse or unknown
a priori. Unexpectedly, this can be true even when the training sets were
automatically translated from English. This finding can have immediate impact
on multilingual zero-shot systems, and should inform future benchmark designs.