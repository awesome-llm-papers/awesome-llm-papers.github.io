---
layout: publication
title: 'Sysformer: Safeguarding Frozen Large Language Models With Adaptive System
  Prompts'
authors: Sharma et al.
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: sharma2025sysformer
citations: 72
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.15751'}]
tags: [Datasets, Training Techniques, Prompting, CVPR, Evaluation, Security, Fine
    Tuning, Responsible AI]
---
As large language models (LLMs) are deployed in safety-critical settings, it is essential to ensure that their responses comply with safety standards. Prior research has revealed that LLMs often fail to grasp the notion of safe behaviors, resulting in either unjustified refusals to harmless prompts or the generation of harmful content. While substantial efforts have been made to improve their robustness, existing defenses often rely on costly fine-tuning of model parameters or employ suboptimal heuristic techniques. In this work, we take a novel approach to safeguard LLMs by learning to adapt the system prompts in instruction-tuned LLMs. While LLMs are typically pre-trained to follow a fixed system prompt, we investigate the impact of tailoring the system prompt to each specific user input on the safety of the responses. To this end, we propose \\(\textbf\{Sysformer\}\\), a trans\\(\textbf\{former\}\\) model that updates an initial \\(\textbf\{sys\}\\)tem prompt to a more robust system prompt in the LLM input embedding space while attending to the user prompt. While keeping the LLM parameters frozen, the Sysformer is trained to refuse to respond to a set of harmful prompts while responding ideally to a set of safe ones. Through extensive experiments on \\(5\\) LLMs from different families and \\(2\\) recent benchmarks, we demonstrate that Sysformer can significantly enhance the robustness of LLMs, leading to upto \\(80%\\) gain in the refusal rate on harmful prompts while enhancing the compliance with the safe prompts by upto \\(90%\\). Results also generalize well to sophisticated jailbreaking attacks, making LLMs upto \\(100%\\) more robust against different attack strategies. We hope our findings lead to cheaper safeguarding of LLMs and motivate future investigations into designing variable system prompts.