---
layout: publication
title: 'Transquest: Translation Quality Estimation With Cross-lingual Transformers'
authors: Ranasinghe Tharindu, Orasan Constantin, Mitkov Ruslan
conference: Proceedings of the 28th International Conference on Computational Linguistics
year: 2020
bibkey: ranasinghe2020transquest
citations: 66
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2011.01536'}]
tags: [Training Techniques, COLING, Evaluation, Tools, Transformer, Model Architecture,
  Fine Tuning, Datasets]
---
Recent years have seen big advances in the field of sentence-level quality
estimation (QE), largely as a result of using neural-based architectures.
However, the majority of these methods work only on the language pair they are
trained on and need retraining for new language pairs. This process can prove
difficult from a technical point of view and is usually computationally
expensive. In this paper we propose a simple QE framework based on
cross-lingual transformers, and we use it to implement and evaluate two
different neural architectures. Our evaluation shows that the proposed methods
achieve state-of-the-art results outperforming current open-source quality
estimation frameworks when trained on datasets from WMT. In addition, the
framework proves very useful in transfer learning settings, especially when
dealing with low-resourced languages, allowing us to obtain very competitive
results.