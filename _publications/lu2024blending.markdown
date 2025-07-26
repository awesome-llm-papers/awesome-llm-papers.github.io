---
layout: publication
title: 'Blending Is All You Need: Cheaper, Better Alternative To Trillion-parameters
  LLM'
authors: Xiaoding Lu, Adian Liusie, Vyas Raina, Yuwen Zhang, William Beauchamp
conference: No Venue
year: 2024
bibkey: lu2024blending
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2401.02994'}]
tags: ["Evaluation", "Tools"]
short_authors: Lu et al.
---
In conversational AI research, there's a noticeable trend towards developing models with a larger number of parameters, exemplified by models like ChatGPT. While these expansive models tend to generate increasingly better chat responses, they demand significant computational resources and memory. This study explores a pertinent question: Can a combination of smaller models collaboratively achieve comparable or enhanced performance relative to a singular large model? We introduce an approach termed "blending", a straightforward yet effective method of integrating multiple chat AIs. Our empirical evidence suggests that when specific smaller models are synergistically blended, they can potentially outperform or match the capabilities of much larger counterparts. For instance, integrating just three models of moderate size (6B/13B paramaeters) can rival or even surpass the performance metrics of a substantially larger model like ChatGPT (175B+ paramaters). This hypothesis is rigorously tested using A/B testing methodologies with a large user base on the Chai research platform over a span of thirty days. The findings underscore the potential of the "blending" strategy as a viable approach for enhancing chat AI efficacy without a corresponding surge in computational demands.

https://huggingface.co/discussions/paper/659cbca053f784cdcabe9422