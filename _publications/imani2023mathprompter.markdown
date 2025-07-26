---
layout: publication
title: 'Mathprompter: Mathematical Reasoning Using Large Language Models'
authors: Shima Imani, Liang Du, Harsh Shrivastava
conference: 'Proceedings of the 61st Annual Meeting of the Association for Computational
  Linguistics (Volume 5: Industry Track)'
year: 2023
bibkey: imani2023mathprompter
citations: 68
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.05398'}]
tags: ["Datasets", "Model Architecture", "Prompting"]
short_authors: Shima Imani, Liang Du, Harsh Shrivastava
---
Large Language Models (LLMs) have limited performance when solving arithmetic
reasoning tasks and often provide incorrect answers. Unlike natural language
understanding, math problems typically have a single correct answer, making the
task of generating accurate solutions more challenging for LLMs. To the best of
our knowledge, we are not aware of any LLMs that indicate their level of
confidence in their responses which fuels a trust deficit in these models
impeding their adoption. To address this deficiency, we propose `MathPrompter',
a technique that improves performance of LLMs on arithmetic problems along with
increased reliance in the predictions. MathPrompter uses the Zero-shot
chain-of-thought prompting technique to generate multiple Algebraic expressions
or Python functions to solve the same math problem in different ways and
thereby raise the confidence level in the output results. This is in contrast
to other prompt based CoT methods, where there is no check on the validity of
the intermediate steps followed. Our technique improves over state-of-the-art
on the MultiArith dataset (\\(78.7%\rightarrow92.5%\\)) evaluated using 175B
parameter GPT-based LLM.