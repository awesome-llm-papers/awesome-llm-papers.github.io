---
layout: publication
title: 'Model Merging And Safety Alignment: One Bad Model Spoils The Bunch'
authors: Hasan Abed Al Kader Hammoud, Umberto Michieli, Fabio Pizzati, Philip Torr,
  Adel Bibi, Bernard Ghanem, Mete Ozay
conference: No Venue
year: 2024
bibkey: hammoud2024model
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2406.14563'}]
tags: ["Efficiency", "Ethics & Fairness"]
short_authors: Hammoud et al.
---
Merging Large Language Models (LLMs) is a cost-effective technique for combining multiple expert LLMs into a single versatile model, retaining the expertise of the original ones. However, current approaches often overlook the importance of safety alignment during merging, leading to highly misaligned models. This work investigates the effects of model merging on alignment. We evaluate several popular model merging techniques, demonstrating that existing methods do not only transfer domain expertise but also propagate misalignment. We propose a simple two-step approach to address this problem: (i) generating synthetic safety and domain-specific data, and (ii) incorporating these generated data into the optimization process of existing data-aware model merging techniques. This allows us to treat alignment as a skill that can be maximized in the resulting merged LLM. Our experiments illustrate the effectiveness of integrating alignment-related data during merging, resulting in models that excel in both domain expertise and alignment.

https://huggingface.co/discussions/paper/6675a374a223121b3da870f4