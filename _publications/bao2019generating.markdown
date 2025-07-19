---
layout: publication
title: Generating Sentences From Disentangled Syntactic And Semantic Spaces
authors: Bao et al.
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: bao2019generating
citations: 91
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1907.05789'}]
tags: [ACL, Applications]
---
Variational auto-encoders (VAEs) are widely used in natural language
generation due to the regularization of the latent space. However, generating
sentences from the continuous latent space does not explicitly model the
syntactic information. In this paper, we propose to generate sentences from
disentangled syntactic and semantic spaces. Our proposed method explicitly
models syntactic information in the VAE's latent space by using the linearized
tree sequence, leading to better performance of language generation.
Additionally, the advantage of sampling in the disentangled syntactic and
semantic latent spaces enables us to perform novel applications, such as the
unsupervised paraphrase generation and syntax-transfer generation. Experimental
results show that our proposed model achieves similar or better performance in
various tasks, compared with state-of-the-art related work.