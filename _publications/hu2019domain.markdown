---
layout: publication
title: Domain Adaptation Of Neural Machine Translation By Lexicon Induction
authors: Junjie Hu, Mengzhou Xia, Graham Neubig, Jaime Carbonell
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: hu2019domain
citations: 65
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.00376'}]
tags: ["Fine-Tuning", "Model Architecture"]
short_authors: Hu et al.
---
It has been previously noted that neural machine translation (NMT) is very
sensitive to domain shift. In this paper, we argue that this is a dual effect
of the highly lexicalized nature of NMT, resulting in failure for sentences
with large numbers of unknown words, and lack of supervision for
domain-specific words. To remedy this problem, we propose an unsupervised
adaptation method which fine-tunes a pre-trained out-of-domain NMT model using
a pseudo-in-domain corpus. Specifically, we perform lexicon induction to
extract an in-domain lexicon, and construct a pseudo-parallel in-domain corpus
by performing word-for-word back-translation of monolingual in-domain target
sentences. In five domains over twenty pairwise adaptation settings and two
model architectures, our method achieves consistent improvements without using
any in-domain parallel sentences, improving up to 14 BLEU over unadapted
models, and up to 2 BLEU over strong back-translation baselines.