---
layout: publication
title: 'Contrastive Decoding: Open-ended Text Generation As Optimization'
authors: Xiang Lisa Li et al.
conference: Arxiv
year: 2022
citations: 18
bibkey: li2022contrastive
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2210.15097'}]
tags: [Training Techniques, GPT, Efficiency and Optimization, Language Modeling, Model
    Architecture]
---
Given a language model (LM), maximum probability is a poor decoding objective
for open-ended generation, because it produces short and repetitive text. On
the other hand, sampling can often produce incoherent text that drifts from the
original topics. We propose contrastive decoding (CD), a reliable decoding
approach that optimizes a contrastive objective subject to a plausibility
constraint. The contrastive objective returns the difference between the
likelihood under a large LM (called the expert, e.g. OPT-13B) and a small LM
(called the amateur, e.g. OPT-125M), and the constraint ensures that the
outputs are plausible. CD is inspired by the fact that the failures of larger
LMs (e.g., repetition, incoherence) are even more prevalent in smaller LMs, and
that this difference signals which texts should be preferred. CD requires zero
additional training, and produces higher quality text than decoding from the
larger LM alone. It also works across model scales (OPT-13B and GPT2-1.5B) and
significantly outperforms four strong decoding algorithms (e.g., nucleus,
top-k) in automatic and human evaluations across wikipedia, news and story
domains.