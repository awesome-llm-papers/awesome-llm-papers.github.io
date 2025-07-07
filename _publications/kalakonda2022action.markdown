---
layout: publication
title: 'Action-gpt: Leveraging Large-scale Language Models For Improved And Generalized
  Action Generation'
authors: Sai Shashank Kalakonda, Shubh Maheshwari, Ravi Kiran Sarvadevabhatla
conference: Arxiv
year: 2022
citations: 28
bibkey: kalakonda2022action
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2211.15603'}]
tags: [GPT, RAG, Tools, Prompting, Model Architecture]
---
We introduce Action-GPT, a plug-and-play framework for incorporating Large
Language Models (LLMs) into text-based action generation models. Action phrases
in current motion capture datasets contain minimal and to-the-point
information. By carefully crafting prompts for LLMs, we generate richer and
fine-grained descriptions of the action. We show that utilizing these detailed
descriptions instead of the original action phrases leads to better alignment
of text and motion spaces. We introduce a generic approach compatible with
stochastic (e.g. VAE-based) and deterministic (e.g. MotionCLIP) text-to-motion
models. In addition, the approach enables multiple text descriptions to be
utilized. Our experiments show (i) noticeable qualitative and quantitative
improvement in the quality of synthesized motions, (ii) benefits of utilizing
multiple LLM-generated descriptions, (iii) suitability of the prompt function,
and (iv) zero-shot generation capabilities of the proposed approach. Project
page: https://actiongpt.github.io