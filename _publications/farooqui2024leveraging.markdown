---
layout: publication
title: Leveraging Linguistically Enhanced Embeddings For Open Information Extraction
authors: Farooqui et al.
conference: 'Proceedings of the 53rd Annual Meeting of the Association for Computational
  Linguistics and the 7th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2024
bibkey: farooqui2024leveraging
citations: 276
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2403.13903'}]
tags: [Datasets, Model Architecture, ACL, RAG]
---
Open Information Extraction (OIE) is a structured prediction (SP) task in
Natural Language Processing (NLP) that aims to extract structured \\(n\\)-ary
tuples - usually subject-relation-object triples - from free text. The word
embeddings in the input text can be enhanced with linguistic features, usually
Part-of-Speech (PoS) and Syntactic Dependency Parse (SynDP) labels. However,
past enhancement techniques cannot leverage the power of pretrained language
models (PLMs), which themselves have been hardly used for OIE. To bridge this
gap, we are the first to leverage linguistic features with a Seq2Seq PLM for
OIE. We do so by introducing two methods - Weighted Addition and Linearized
Concatenation. Our work can give any neural OIE architecture the key
performance boost from both PLMs and linguistic features in one go. In our
settings, this shows wide improvements of up to 24.9%, 27.3% and 14.9% on
Precision, Recall and F1 scores respectively over the baseline. Beyond this, we
address other important challenges in the field: to reduce compute overheads
with the features, we are the first ones to exploit Semantic Dependency Parse
(SemDP) tags; to address flaws in current datasets, we create a clean synthetic
dataset; finally, we contribute the first known study of OIE behaviour in SP
models.