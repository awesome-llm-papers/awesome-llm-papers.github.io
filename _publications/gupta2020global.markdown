---
layout: publication
title: 'GMAT: Global Memory Augmentation For Transformers'
authors: Ankit Gupta, Jonathan Berant
conference: Arxiv
year: 2020
citations: 25
bibkey: gupta2020global
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2006.03274'}]
tags: [Language Modeling, Model Architecture, Attention Mechanism, Transformer, Masked
    Language Model, BERT]
---
Transformer-based models have become ubiquitous in natural language
processing thanks to their large capacity, innate parallelism and high
performance. The contextualizing component of a Transformer block is the
\\(\textit\{pairwise dot-product\}\\) attention that has a large \\(Ω(L^2)\\) memory
requirement for length \\(L\\) sequences, limiting its ability to process long
documents. This has been the subject of substantial interest recently, where
multiple approximations were proposed to reduce the quadratic memory
requirement using sparse attention matrices. In this work, we propose to
augment sparse Transformer blocks with a dense attention-based \\(\textit\{global
memory\}\\) of length \\(M\\) (\\(\ll L\\)) which provides an aggregate global view of the
entire input sequence to each position. Our augmentation has a manageable
\\(O(M\cdot(L+M))\\) memory overhead, and can be seamlessly integrated with prior
sparse solutions. Moreover, global memory can also be used for sequence
compression, by representing a long input sequence with the memory
representations only. We empirically show that our method leads to substantial
improvement on a range of tasks, including (a) synthetic tasks that require
global reasoning, (b) masked language modeling, and (c) reading comprehension.