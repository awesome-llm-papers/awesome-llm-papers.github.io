---
layout: publication
title: Informative Language Representation Learning For Massively Multilingual Neural
  Machine Translation
authors: Jin Renren, Xiong Deyi
conference: Proceedings of the 2019 Conference of the North
year: 2022
bibkey: jin2022informative
citations: 81
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2209.01530'}]
tags: [Datasets, Model Architecture, Attention Mechanism]
---
In a multilingual neural machine translation model that fully shares
parameters across all languages, an artificial language token is usually used
to guide translation into the desired target language. However, recent studies
show that prepending language tokens sometimes fails to navigate the
multilingual neural machine translation models into right translation
directions, especially on zero-shot translation. To mitigate this issue, we
propose two methods, language embedding embodiment and language-aware
multi-head attention, to learn informative language representations to channel
translation into right directions. The former embodies language embeddings into
different critical switching points along the information flow from the source
to the target, aiming at amplifying translation direction guiding signals. The
latter exploits a matrix, instead of a vector, to represent a language in the
continuous space. The matrix is chunked into multiple heads so as to learn
language representations in multiple subspaces. Experiment results on two
datasets for massively multilingual neural machine translation demonstrate that
language-aware multi-head attention benefits both supervised and zero-shot
translation and significantly alleviates the off-target translation issue.
Further linguistic typology prediction experiments show that matrix-based
language representations learned by our methods are capable of capturing rich
linguistic typology features.