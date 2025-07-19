---
layout: publication
title: 'Wizardcoder: Empowering Code Large Language Models With Evol-instruct'
authors: Luo et al.
conference: The Twelfth International Conference on Learning Representations (ICLR
  2024)
year: 2023
bibkey: luo2023wizardcoder
citations: 58
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2306.08568'}]
tags: [Training Techniques, Evaluation, ICLR, Fine Tuning, Datasets, LLM For Code]
---
Code Large Language Models (Code LLMs), such as StarCoder, have demonstrated exceptional performance in code-related tasks. However, most existing models are solely pre-trained on extensive raw code data without instruction fine-tuning. In this paper, we introduce WizardCoder, which empowers Code LLMs with complex instruction fine-tuning, by adapting the Evol-Instruct method to the domain of code. Through comprehensive experiments on four prominent code generation benchmarks, namely HumanEval, HumanEval+, MBPP, and DS-1000, we unveil the exceptional capabilities of our model. It surpasses all other open-source Code LLMs by a substantial margin. Moreover, our model even outperforms the largest closed LLMs, Anthropic's Claude and Google's Bard, on HumanEval and HumanEval+. Our code, model weights, and data are public at https://github.com/nlpxucan/WizardLM