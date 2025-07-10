---
layout: publication
title: Revealing Persona Biases In Dialogue Systems
authors: Emily Sheng, Josh Arnold, Zhou Yu, Kai-wei Chang, Nanyun Peng
conference: Arxiv
year: 2021
citations: 21
bibkey: sheng2021revealing
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.08728'}]
tags: [Tools, GPT, Model Architecture, Ethics and Bias]
---
Dialogue systems in the form of chatbots and personal assistants are being
increasingly integrated into people's lives. Modern dialogue systems may
consider adopting anthropomorphic personas, mimicking societal demographic
groups to appear more approachable and trustworthy to users. However, the
adoption of a persona can result in the adoption of biases. In this paper, we
present the first large-scale study on persona biases in dialogue systems and
conduct analyses on personas of different social classes, sexual orientations,
races, and genders. We define persona biases as harmful differences in
responses (e.g., varying levels of offensiveness, agreement with harmful
statements) generated from adopting different demographic personas.
Furthermore, we introduce an open-source framework, UnitPersonaBias, to explore
and aggregate persona biases in dialogue systems. By analyzing the Blender and
DialoGPT dialogue systems, we observe that adopting personas can actually
decrease harmful responses, compared to not using any personas. Additionally,
we find that persona choices can affect the degree of harms in generated
responses and thus should be systematically evaluated before deployment. We
also analyze how personas can result in different amounts of harm towards
specific demographics.