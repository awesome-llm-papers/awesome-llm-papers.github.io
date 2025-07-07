---
layout: publication
title: 'Mariogpt: Open-ended Text2level Generation Through Large Language Models'
authors: Shyam Sudhakaran et al.
conference: Arxiv
year: 2023
citations: 15
bibkey: sudhakaran2023open
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2302.05981'}, {name: Code,
    url: 'https://github.com/shyamsn97/mario-gpt'}]
tags: [Training Techniques, GPT, Has Code, Prompting, Model Architecture]
---
Procedural Content Generation (PCG) is a technique to generate complex and
diverse environments in an automated way. However, while generating content
with PCG methods is often straightforward, generating meaningful content that
reflects specific intentions and constraints remains challenging. Furthermore,
many PCG algorithms lack the ability to generate content in an open-ended
manner. Recently, Large Language Models (LLMs) have shown to be incredibly
effective in many diverse domains. These trained LLMs can be fine-tuned,
re-using information and accelerating training for new tasks. Here, we
introduce MarioGPT, a fine-tuned GPT2 model trained to generate tile-based game
levels, in our case Super Mario Bros levels. MarioGPT can not only generate
diverse levels, but can be text-prompted for controllable level generation,
addressing one of the key challenges of current PCG techniques. As far as we
know, MarioGPT is the first text-to-level model and combined with novelty
search it enables the generation of diverse levels with varying play-style
dynamics (i.e. player paths) and the open-ended discovery of an increasingly
diverse range of content. Code available at
https://github.com/shyamsn97/mario-gpt.