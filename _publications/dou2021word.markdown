---
layout: publication
title: Word Alignment By Fine-tuning Embeddings On Parallel Corpora
authors: Dou Zi-yi, Neubig Graham
conference: 'Proceedings of the 16th Conference of the European Chapter of the Association
  for Computational Linguistics: Main Volume'
year: 2021
bibkey: dou2021word
citations: 106
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2101.08231'}]
tags: [Tools, Training Techniques, Fine Tuning, Evaluation, ACL, Applications, RAG,
  EACL, Alt]
---
Word alignment over parallel corpora has a wide variety of applications,
including learning translation lexicons, cross-lingual transfer of language
processing tools, and automatic evaluation or analysis of translation outputs.
The great majority of past work on word alignment has worked by performing
unsupervised learning on parallel texts. Recently, however, other work has
demonstrated that pre-trained contextualized word embeddings derived from
multilingually trained language models (LMs) prove an attractive alternative,
achieving competitive results on the word alignment task even in the absence of
explicit training on parallel data. In this paper, we examine methods to marry
the two approaches: leveraging pre-trained LMs but fine-tuning them on parallel
text with objectives designed to improve alignment quality, and proposing
methods to effectively extract alignments from these fine-tuned models. We
perform experiments on five language pairs and demonstrate that our model can
consistently outperform previous state-of-the-art models of all varieties. In
addition, we demonstrate that we are able to train multilingual word aligners
that can obtain robust performance on different language pairs. Our aligner,
AWESOME (Aligning Word Embedding Spaces of Multilingual Encoders), with
pre-trained models is available at https://github.com/neulab/awesome-align