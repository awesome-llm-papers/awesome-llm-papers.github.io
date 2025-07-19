---
layout: publication
title: Chain-of-verification Reduces Hallucination In Large Language Models
authors: Dhuliawala et al.
conference: Findings of the Association for Computational Linguistics ACL 2024
year: 2023
bibkey: dhuliawala2023chain
citations: 62
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2309.11495'}]
tags: [ACL, Ethics And Bias, Language Modeling]
---
Generation of plausible yet incorrect factual information, termed
hallucination, is an unsolved issue in large language models. We study the
ability of language models to deliberate on the responses they give in order to
correct their mistakes. We develop the Chain-of-Verification (CoVe) method
whereby the model first (i) drafts an initial response; then (ii) plans
verification questions to fact-check its draft; (iii) answers those questions
independently so the answers are not biased by other responses; and (iv)
generates its final verified response. In experiments, we show CoVe decreases
hallucinations across a variety of tasks, from list-based questions from
Wikidata, closed book MultiSpanQA and longform text generation.