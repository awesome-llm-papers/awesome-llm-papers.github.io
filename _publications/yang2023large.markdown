---
layout: publication
title: Large Language Models As Optimizers
authors: Chengrun Yang, Xuezhi Wang, Yifeng Lu, Hanxiao Liu, Quoc V. Le, Denny Zhou,
  Xinyun Chen
conference: No Venue
year: 2023
bibkey: yang2023large
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2309.03409'}]
tags: ["Applications", "Tools"]
short_authors: Yang et al.
---
Optimization is ubiquitous. While derivative-based algorithms have been powerful tools for various problems, the absence of gradient imposes challenges on many real-world applications. In this work, we propose Optimization by PROmpting (OPRO), a simple and effective approach to leverage large language models (LLMs) as optimizers, where the optimization task is described in natural language. In each optimization step, the LLM generates new solutions from the prompt that contains previously generated solutions with their values, then the new solutions are evaluated and added to the prompt for the next optimization step. We first showcase OPRO on linear regression and traveling salesman problems, then move on to prompt optimization where the goal is to find instructions that maximize the task accuracy. With a variety of LLMs, we demonstrate that the best prompts optimized by OPRO outperform human-designed prompts by up to 8% on GSM8K, and by up to 50% on Big-Bench Hard tasks.

https://huggingface.co/discussions/paper/64fa7df2dcc5ce730e443fbd