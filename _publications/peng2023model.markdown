---
layout: publication
title: Model Tuning Or Prompt Tuning? A Study Of Large Language Models For Clinical
  Concept And Relation Extraction
authors: Cheng Peng et al.
conference: Journal of Biomedical Informatics
year: 2023
citations: 24
bibkey: peng2023model
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.06239'}]
tags: [Fine-Tuning, Few-Shot, Applications, Prompting, Training Techniques, Evaluation]
---
Objective To develop soft prompt-based learning algorithms for large language
models (LLMs), examine the shape of prompts, prompt-tuning using
frozen/unfrozen LLMs, transfer learning, and few-shot learning abilities.
Methods We developed a soft prompt-based LLM model and compared 4 training
strategies including (1) fine-tuning without prompts; (2) hard-prompt with
unfrozen LLMs; (3) soft-prompt with unfrozen LLMs; and (4) soft-prompt with
frozen LLMs. We evaluated 7 pretrained LLMs using the 4 training strategies for
clinical concept and relation extraction on two benchmark datasets. We
evaluated the transfer learning ability of the prompt-based learning algorithms
in a cross-institution setting. We also assessed the few-shot learning ability.
Results and Conclusion When LLMs are unfrozen, GatorTron-3.9B with soft
prompting achieves the best strict F1-scores of 0.9118 and 0.8604 for concept
extraction, outperforming the traditional fine-tuning and hard prompt-based
models by 0.6~3.1% and 1.2~2.9%, respectively; GatorTron-345M with soft
prompting achieves the best F1-scores of 0.8332 and 0.7488 for end-to-end
relation extraction, outperforming the other two models by 0.2~2% and
0.6~11.7%, respectively. When LLMs are frozen, small (i.e., 345 million
parameters) LLMs have a big gap to be competitive with unfrozen models; scaling
LLMs up to billions of parameters makes frozen LLMs competitive with unfrozen
LLMs. For cross-institute evaluation, soft prompting with a frozen
GatorTron-8.9B model achieved the best performance. This study demonstrates
that (1) machines can learn soft prompts better than humans, (2) frozen LLMs
have better few-shot learning ability and transfer learning ability to
facilitate muti-institution applications, and (3) frozen LLMs require large
models.