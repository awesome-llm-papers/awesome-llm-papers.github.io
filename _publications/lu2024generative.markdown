---
layout: publication
title: Generative World Explorer
authors: Taiming Lu, Tianmin Shu, Alan Yuille, Daniel Khashabi, Jieneng Chen
conference: No Venue
year: 2024
bibkey: lu2024generative
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2411.11844'}]
tags: ["Agentic", "Datasets", "Tools"]
short_authors: Lu et al.
---
Planning with partial observation is a central challenge in embodied AI. A majority of prior works have tackled this challenge by developing agents that physically explore their environment to update their beliefs about the world state.In contrast, humans can imagine unseen parts of the world through a mental exploration and revise their beliefs with imagined observations. Such updated beliefs can allow them to make more informed decisions, without necessitating the physical exploration of the world at all times. To achieve this human-like ability, we introduce the Generative World Explorer (Genex), an egocentric world exploration framework that allows an agent to mentally explore a large-scale 3D world (e.g., urban scenes) and acquire imagined observations to update its belief. This updated belief will then help the agent to make a more informed decision at the current step. To train Genex, we create a synthetic urban scene dataset, Genex-DB. Our experimental results demonstrate that (1) Genex can generate high-quality and consistent observations during long-horizon exploration of a large virtual physical world and (2) the beliefs updated with the generated observations can inform an existing decision-making model (e.g., an LLM agent) to make better plans.

https://huggingface.co/discussions/paper/673bfe502bf4163ef13f4a96