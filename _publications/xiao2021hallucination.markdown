---
layout: publication
title: On Hallucination And Predictive Uncertainty In Conditional Language Generation
authors: Yijun Xiao, William Yang Wang
conference: Arxiv
year: 2021
citations: 36
bibkey: xiao2021hallucination
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2103.15025'}]
tags: [Language Modeling, Interpretability and Explainability]
---
Despite improvements in performances on different natural language generation
tasks, deep neural models are prone to hallucinating facts that are incorrect
or nonexistent. Different hypotheses are proposed and examined separately for
different tasks, but no systematic explanations are available across these
tasks. In this study, we draw connections between hallucinations and predictive
uncertainty in conditional language generation. We investigate their
relationship in both image captioning and data-to-text generation and propose a
simple extension to beam search to reduce hallucination. Our analysis shows
that higher predictive uncertainty corresponds to a higher chance of
hallucination. Epistemic uncertainty is more indicative of hallucination than
aleatoric or total uncertainties. It helps to achieve better results of trading
performance in standard metric for less hallucination with the proposed beam
search variant.