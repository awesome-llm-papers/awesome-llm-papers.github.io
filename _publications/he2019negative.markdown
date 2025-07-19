---
layout: publication
title: Negative Training For Neural Dialogue Response Generation
authors: He Tianxing, Glass James
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: he2019negative
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1903.02134'}]
tags: [Tools, Fine Tuning, Training Techniques, ACL, RAG, Alt]
---
Although deep learning models have brought tremendous advancements to the
field of open-domain dialogue response generation, recent research results have
revealed that the trained models have undesirable generation behaviors, such as
malicious responses and generic (boring) responses. In this work, we propose a
framework named "Negative Training" to minimize such behaviors. Given a trained
model, the framework will first find generated samples that exhibit the
undesirable behavior, and then use them to feed negative training signals for
fine-tuning the model. Our experiments show that negative training can
significantly reduce the hit rate of malicious responses, or discourage
frequent responses and improve response diversity.