---
layout: publication
title: Training Bilingual Lms With Data Constraints In The Targeted Language
authors: Seto et al.
conference: Cognition
year: 2024
bibkey: seto2024training
citations: 221
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2411.12986'}]
tags: [Scaling Laws, Training Techniques, ASRU, CVPR, Efficiency And Optimization,
  Large Scale Training, Datasets]
---
Large language models are trained on massive scrapes of the web, as required
by current scaling laws. Most progress is made for English, given its abundance
of high-quality pretraining data. For most other languages, however, such high
quality pretraining data is unavailable. In this work, we study how to boost
pretrained model performance in a target language with insufficient pretraining
data for training a high performing language model, by enlisting data from an
auxiliary language for which high quality data is available. We study this by
quantifying the performance gap between training with data in a data-rich
auxiliary language compared with training in the target language, exploring the
benefits of translation systems, studying the limitations of model scaling when
data is limited in the target languages, and proposing new methods for
upsampling data from the auxiliary language. Our results show that stronger
auxiliary datasets result in performance gains without modification to the
model or training objective for close languages, and, in particular, that
performance gains due to the development of more information-rich English
pretraining datasets can extend to targeted language settings with limited
data.