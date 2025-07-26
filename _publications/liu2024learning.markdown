---
layout: publication
title: 'Learning To Refuse: Towards Mitigating Privacy Risks In Llms'
authors: Zhenhua Liu, Tong Zhu, Chuanyuan Tan, Wenliang Chen
conference: No Venue
year: 2024
bibkey: liu2024learning
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2407.10058'}]
tags: ["Privacy"]
short_authors: Liu et al.
---
Large language models (LLMs) exhibit remarkable capabilities in understanding and generating natural language. However, these models can inadvertently memorize private information, posing significant privacy risks. This study addresses the challenge of enabling LLMs to protect specific individuals' private data without the need for complete retraining. We propose \return, a Real-world pErsonal daTa UnleaRNing dataset, comprising 2,492 individuals from Wikipedia with associated QA pairs, to evaluate machine unlearning (MU) methods for protecting personal data in a realistic scenario. Additionally, we introduce the Name-Aware Unlearning Framework (NAUF) for Privacy Protection, which enables the model to learn which individuals' information should be protected without affecting its ability to answer questions related to other unrelated individuals. Our extensive experiments demonstrate that NAUF achieves a state-of-the-art average unlearning score, surpassing the best baseline method by 5.65 points, effectively protecting target individuals' personal data while maintaining the model's general capabilities.

https://huggingface.co/discussions/paper/66960be1659a52fa2757aed4