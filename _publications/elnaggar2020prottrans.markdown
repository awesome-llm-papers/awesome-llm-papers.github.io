---
layout: publication
title: 'Prottrans: Towards Cracking The Language Of Life''s Code Through Self-supervised
  Deep Learning And High Performance Computing'
authors: Elnaggar et al.
conference: Arxiv
year: 2020
bibkey: elnaggar2020prottrans
citations: 196
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2007.06225'}]
tags: [Training Techniques, BERT, Transformer, Model Architecture]
---
Computational biology and bioinformatics provide vast data gold-mines from
protein sequences, ideal for Language Models taken from NLP. These LMs reach
for new prediction frontiers at low inference costs. Here, we trained two
auto-regressive models (Transformer-XL, XLNet) and four auto-encoder models
(BERT, Albert, Electra, T5) on data from UniRef and BFD containing up to 393
billion amino acids. The LMs were trained on the Summit supercomputer using
5616 GPUs and TPU Pod up-to 1024 cores. Dimensionality reduction revealed that
the raw protein LM-embeddings from unlabeled data captured some biophysical
features of protein sequences. We validated the advantage of using the
embeddings as exclusive input for several subsequent tasks. The first was a
per-residue prediction of protein secondary structure (3-state accuracy
Q3=81%-87%); the second were per-protein predictions of protein sub-cellular
localization (ten-state accuracy: Q10=81%) and membrane vs. water-soluble
(2-state accuracy Q2=91%). For the per-residue predictions the transfer of the
most informative embeddings (ProtT5) for the first time outperformed the
state-of-the-art without using evolutionary information thereby bypassing
expensive database searches. Taken together, the results implied that protein
LMs learned some of the grammar of the language of life. To facilitate future
work, we released our models at https://github.com/agemagician/ProtTrans.