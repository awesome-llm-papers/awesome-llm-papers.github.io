---
layout: publication
title: A Novel Graph-based Multi-modal Fusion Encoder For Neural Machine Translation
authors: Yin et al.
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: yin2020novel
citations: 125
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2007.08742'}]
tags: [Model Architecture, Merging, ACL, Datasets, Attention Mechanism]
---
Multi-modal neural machine translation (NMT) aims to translate source
sentences into a target language paired with images. However, dominant
multi-modal NMT models do not fully exploit fine-grained semantic
correspondences between semantic units of different modalities, which have
potential to refine multi-modal representation learning. To deal with this
issue, in this paper, we propose a novel graph-based multi-modal fusion encoder
for NMT. Specifically, we first represent the input sentence and image using a
unified multi-modal graph, which captures various semantic relationships
between multi-modal semantic units (words and visual objects). We then stack
multiple graph-based multi-modal fusion layers that iteratively perform
semantic interactions to learn node representations. Finally, these
representations provide an attention-based context vector for the decoder. We
evaluate our proposed encoder on the Multi30K datasets. Experimental results
and in-depth analysis show the superiority of our multi-modal NMT model.