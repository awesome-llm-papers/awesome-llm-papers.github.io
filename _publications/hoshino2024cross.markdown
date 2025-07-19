---
layout: publication
title: Cross-lingual Transfer Or Machine Translation? On Data Augmentation For Monolingual
  Semantic Textual Similarity
authors: Hoshino et al.
conference: Proceedings of the 10th International Workshop on Semantic Evaluation
  (SemEval-2016)
year: 2024
bibkey: hoshino2024cross
citations: 195
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2403.05257'}]
tags: [RAG, Training Techniques, Masked Language Model, Evaluation, BERT, Fine Tuning,
  Datasets]
---
Learning better sentence embeddings leads to improved performance for natural
language understanding tasks including semantic textual similarity (STS) and
natural language inference (NLI). As prior studies leverage large-scale labeled
NLI datasets for fine-tuning masked language models to yield sentence
embeddings, task performance for languages other than English is often left
behind. In this study, we directly compared two data augmentation techniques as
potential solutions for monolingual STS: (a) cross-lingual transfer that
exploits English resources alone as training data to yield non-English sentence
embeddings as zero-shot inference, and (b) machine translation that coverts
English data into pseudo non-English training data in advance. In our
experiments on monolingual STS in Japanese and Korean, we find that the two
data techniques yield performance on par. Rather, we find a superiority of the
Wikipedia domain over the NLI domain for these languages, in contrast to prior
studies that focused on NLI as training data. Combining our findings, we
demonstrate that the cross-lingual transfer of Wikipedia data exhibits improved
performance, and that native Wikipedia data can further improve performance for
monolingual STS.