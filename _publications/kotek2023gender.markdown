---
layout: publication
title: Gender Bias And Stereotypes In Large Language Models
authors: Hadas Kotek, Rikker Dockum, David Q. Sun
conference: Proceedings of The ACM Collective Intelligence Conference
year: 2023
bibkey: kotek2023gender
citations: 155
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2308.14921'}]
tags: ["Ethics & Fairness"]
short_authors: Hadas Kotek, Rikker Dockum, David Q. Sun
---
Large Language Models (LLMs) have made substantial progress in the past
several months, shattering state-of-the-art benchmarks in many domains. This
paper investigates LLMs' behavior with respect to gender stereotypes, a known
issue for prior models. We use a simple paradigm to test the presence of gender
bias, building on but differing from WinoBias, a commonly used gender bias
dataset, which is likely to be included in the training data of current LLMs.
We test four recently published LLMs and demonstrate that they express biased
assumptions about men and women's occupations. Our contributions in this paper
are as follows: (a) LLMs are 3-6 times more likely to choose an occupation that
stereotypically aligns with a person's gender; (b) these choices align with
people's perceptions better than with the ground truth as reflected in official
job statistics; (c) LLMs in fact amplify the bias beyond what is reflected in
perceptions or the ground truth; (d) LLMs ignore crucial ambiguities in
sentence structure 95% of the time in our study items, but when explicitly
prompted, they recognize the ambiguity; (e) LLMs provide explanations for their
choices that are factually inaccurate and likely obscure the true reason behind
their predictions. That is, they provide rationalizations of their biased
behavior. This highlights a key property of these models: LLMs are trained on
imbalanced datasets; as such, even with the recent successes of reinforcement
learning with human feedback, they tend to reflect those imbalances back at us.
As with other types of societal biases, we suggest that LLMs must be carefully
tested to ensure that they treat minoritized individuals and communities
equitably.