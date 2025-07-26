---
layout: publication
title: Iterative Reasoning Preference Optimization
authors: Richard Yuanzhe Pang, Weizhe Yuan, Kyunghyun Cho, He He, Sainbayar Sukhbaatar,
  Jason Weston
conference: No Venue
year: 2024
bibkey: pang2024iterative
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2404.19733'}]
tags: ["Datasets", "Efficiency", "Prompting", "Reinforcement Learning", "Training Techniques"]
short_authors: Pang et al.
---
Iterative preference optimization methods have recently been shown to perform well for general instruction tuning tasks, but typically make little improvement on reasoning tasks (Yuan et al., 2024, Chen et al., 2024). In this work we develop an iterative approach that optimizes the preference between competing generated Chain-of-Thought (CoT) candidates by optimizing for winning vs. losing reasoning steps that lead to the correct answer. We train using a modified DPO loss (Rafailov et al., 2023) with an additional negative log-likelihood term, which we find to be crucial. We show reasoning improves across repeated iterations of this scheme. While only relying on examples in the training set, our approach results in increasing accuracy for Llama-2-70B-Chat from 55.6% to 81.6% on GSM8K (and 88.7% with majority voting out of 32 samples), from 12.5% to 20.8% on MATH, and from 77.8% to 86.7% on ARC-Challenge, which outperforms other Llama-2-based models not relying on additionally sourced datasets.

https://huggingface.co/discussions/paper/6631a5d4992449cefe049b26