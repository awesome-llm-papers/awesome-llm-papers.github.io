---
layout: publication
title: Contrastive Search Is What You Need For Neural Text Generation
authors: Yixuan Su, Nigel Collier
conference: Arxiv
year: 2022
bibkey: su2022contrastive
citations: 80
additional_links: [{name: Code, url: 'https://github.com/yxuansu/Contrastive_Search_Is_What_You_Need'},
  {name: Paper, url: 'https://arxiv.org/abs/2210.14140'}]
tags: ["Applications", "Model Architecture", "Training Techniques"]
short_authors: Yixuan Su, Nigel Collier
---
Generating text with autoregressive language models (LMs) is of great
importance to many natural language processing (NLP) applications. Previous
solutions for this task often produce text that contains degenerative
expressions or lacks semantic consistency. Recently, Su et al. introduced a new
decoding method, contrastive search, based on the isotropic representation
space of the language model and obtained new state of the art on various
benchmarks. Additionally, Su et al. argued that the representations of
autoregressive LMs (e.g. GPT-2) are intrinsically anisotropic which is also
shared by previous studies. Therefore, to ensure the language model follows an
isotropic distribution, Su et al. proposed a contrastive learning scheme,
SimCTG, which calibrates the language model's representations through
additional training.
  In this study, we first answer the question: "Are autoregressive LMs really
anisotropic?". To this end, we extensively evaluate the isotropy of LMs across
16 major languages. Surprisingly, we find that the anisotropic problem only
exists in the two specific English GPT-2-small/medium models. On the other
hand, all other evaluated LMs are naturally isotropic which is in contrast to
the conclusion drawn by previous studies. Based on our findings, we further
assess the contrastive search decoding method using off-the-shelf LMs on four
generation tasks across 16 languages. Our experimental results demonstrate that
contrastive search significantly outperforms previous decoding methods without
any additional training. More notably, on 12 out of the 16 evaluated languages,
contrastive search performs comparably with human-level performances as judged
by human evaluations. Our code and other related resources are publicly
available at https://github.com/yxuansu/Contrastive_Search_Is_What_You_Need.