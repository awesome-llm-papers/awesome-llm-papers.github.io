---
layout: publication
title: 'Augmented SBERT: Data Augmentation Method For Improving Bi-encoders For Pairwise
  Sentence Scoring Tasks'
authors: Thakur et al.
conference: 'Proceedings of the 2021 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2020
bibkey: thakur2020augmented
citations: 139
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.08240'}]
tags: [Model Architecture, Training Techniques, Fine Tuning, BERT, ACL, Applications,
  NAACL, Attention Mechanism]
---
There are two approaches for pairwise sentence scoring: Cross-encoders, which
perform full-attention over the input pair, and Bi-encoders, which map each
input independently to a dense vector space. While cross-encoders often achieve
higher performance, they are too slow for many practical use cases.
Bi-encoders, on the other hand, require substantial training data and
fine-tuning over the target task to achieve competitive performance. We present
a simple yet efficient data augmentation strategy called Augmented SBERT, where
we use the cross-encoder to label a larger set of input pairs to augment the
training data for the bi-encoder. We show that, in this process, selecting the
sentence pairs is non-trivial and crucial for the success of the method. We
evaluate our approach on multiple tasks (in-domain) as well as on a domain
adaptation task. Augmented SBERT achieves an improvement of up to 6 points for
in-domain and of up to 37 points for domain adaptation tasks compared to the
original bi-encoder performance.