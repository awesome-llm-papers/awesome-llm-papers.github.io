---
layout: publication
title: Exploring Visual Prompts For Adapting Large-scale Models
authors: Hyojin Bahng, Ali Jahanian, Swami Sankaranarayanan, Phillip Isola
conference: Arxiv
year: 2022
bibkey: bahng2022exploring
citations: 97
additional_links: [{name: Code, url: 'http://hjbahng.github.io/visual_prompting'},
  {name: Paper, url: 'https://arxiv.org/abs/2203.17274'}]
tags: ["Prompting"]
short_authors: Bahng et al.
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