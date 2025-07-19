---
layout: publication
title: Exploring Visual Prompts For Adapting Large-scale Models
authors: Bahng et al.
conference: Arxiv
year: 2022
bibkey: bahng2022exploring
citations: 95
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.17274'}]
tags: [Prompting, Security, Reinforcement Learning, Datasets]
---
We investigate the efficacy of visual prompting to adapt large-scale models
in vision. Following the recent approach from prompt tuning and adversarial
reprogramming, we learn a single image perturbation such that a frozen model
prompted with this perturbation performs a new task. Through comprehensive
experiments, we demonstrate that visual prompting is particularly effective for
CLIP and robust to distribution shift, achieving performance competitive with
standard linear probes. We further analyze properties of the downstream
dataset, prompt design, and output transformation in regard to adaptation
performance. The surprising effectiveness of visual prompting provides a new
perspective on adapting pre-trained models in vision. Code is available at
http://hjbahng.github.io/visual_prompting .