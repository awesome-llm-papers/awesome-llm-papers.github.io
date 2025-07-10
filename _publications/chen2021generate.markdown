---
layout: publication
title: Generate Natural Language Explanations For Recommendation
authors: Hanxiong Chen, Xu Chen, Shaoyun Shi, Yongfeng Zhang
conference: Arxiv
year: 2021
citations: 38
bibkey: chen2021generate
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2101.03392'}]
tags: [Ethics and Bias, RAG, RecSys, Reinforcement Learning, Interpretability and
    Explainability, Agentic]
---
Providing personalized explanations for recommendations can help users to
understand the underlying insight of the recommendation results, which is
helpful to the effectiveness, transparency, persuasiveness and trustworthiness
of recommender systems. Current explainable recommendation models mostly
generate textual explanations based on pre-defined sentence templates. However,
the expressiveness power of template-based explanation sentences are limited to
the pre-defined expressions, and manually defining the expressions require
significant human efforts. Motivated by this problem, we propose to generate
free-text natural language explanations for personalized recommendation. In
particular, we propose a hierarchical sequence-to-sequence model (HSS) for
personalized explanation generation. Different from conventional sentence
generation in NLP research, a great challenge of explanation generation in
e-commerce recommendation is that not all sentences in user reviews are of
explanation purpose. To solve the problem, we further propose an auto-denoising
mechanism based on topical item feature words for sentence generation.
Experiments on various e-commerce product domains show that our approach can
not only improve the recommendation accuracy, but also the explanation quality
in terms of the offline measures and feature words coverage. This research is
one of the initial steps to grant intelligent agents with the ability to
explain itself based on natural language sentences.