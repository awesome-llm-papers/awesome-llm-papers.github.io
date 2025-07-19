---
layout: publication
title: Protected Group Bias And Stereotypes In Large Language Models
authors: Kotek et al.
conference: Proceedings of The ACM Collective Intelligence Conference
year: 2024
bibkey: kotek2024protected
citations: 152
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2403.14727'}]
tags: [Datasets, Fairness, Training Techniques, Bias Mitigation, Evaluation, Ethics
    And Bias, Reinforcement Learning, Responsible AI]
---
As modern Large Language Models (LLMs) shatter many state-of-the-art
benchmarks in a variety of domains, this paper investigates their behavior in
the domains of ethics and fairness, focusing on protected group bias. We
conduct a two-part study: first, we solicit sentence continuations describing
the occupations of individuals from different protected groups, including
gender, sexuality, religion, and race. Second, we have the model generate
stories about individuals who hold different types of occupations. We collect
>10k sentence completions made by a publicly available LLM, which we subject to
human annotation. We find bias across minoritized groups, but in particular in
the domains of gender and sexuality, as well as Western bias, in model
generations. The model not only reflects societal biases, but appears to
amplify them. The model is additionally overly cautious in replies to queries
relating to minoritized groups, providing responses that strongly emphasize
diversity and equity to an extent that other group characteristics are
overshadowed. This suggests that artificially constraining potentially harmful
outputs may itself lead to harm, and should be applied in a careful and
controlled manner.