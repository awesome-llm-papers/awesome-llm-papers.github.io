---
layout: publication
title: 'PSSL: Self-supervised Learning For Personalized Search With Contrastive Sampling'
authors: Zhou et al.
conference: Proceedings of the 29th ACM International Conference on Multimedia
year: 2021
bibkey: zhou2021pssl
citations: 60
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2111.12614'}]
tags: [Tools, Training Techniques, Datasets]
---
Personalized search plays a crucial role in improving user search experience
owing to its ability to build user profiles based on historical behaviors.
Previous studies have made great progress in extracting personal signals from
the query log and learning user representations. However, neural personalized
search is extremely dependent on sufficient data to train the user model. Data
sparsity is an inevitable challenge for existing methods to learn high-quality
user representations. Moreover, the overemphasis on final ranking quality leads
to rough data representations and impairs the generalizability of the model. To
tackle these issues, we propose a Personalized Search framework with
Self-supervised Learning (PSSL) to enhance data representations. Specifically,
we adopt a contrastive sampling method to extract paired self-supervised
information from sequences of user behaviors in query logs. Four auxiliary
tasks are designed to pre-train the sentence encoder and the sequence encoder
used in the ranking model. They are optimized by contrastive loss which aims to
close the distance between similar user sequences, queries, and documents.
Experimental results on two datasets demonstrate that our proposed model PSSL
achieves state-of-the-art performance compared with existing baselines.