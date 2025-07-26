---
layout: publication
title: Interactive And Visual Prompt Engineering For Ad-hoc Task Adaptation With Large
  Language Models
authors: Hendrik Strobelt, Albert Webson, Victor Sanh, Benjamin Hoover, Johanna Beyer,
  Hanspeter Pfister, Alexander M. Rush
conference: IEEE Transactions on Visualization and Computer Graphics
year: 2022
bibkey: strobelt2022interactive
citations: 118
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2208.07852'}]
tags: ["Applications", "Prompting"]
short_authors: Strobelt et al.
---
State-of-the-art neural language models can now be used to solve ad-hoc
language tasks through zero-shot prompting without the need for supervised
training. This approach has gained popularity in recent years, and researchers
have demonstrated prompts that achieve strong accuracy on specific NLP tasks.
However, finding a prompt for new tasks requires experimentation. Different
prompt templates with different wording choices lead to significant accuracy
differences. PromptIDE allows users to experiment with prompt variations,
visualize prompt performance, and iteratively optimize prompts. We developed a
workflow that allows users to first focus on model feedback using small data
before moving on to a large data regime that allows empirical grounding of
promising prompts using quantitative measures of the task. The tool then allows
easy deployment of the newly created ad-hoc models. We demonstrate the utility
of PromptIDE (demo at http://prompt.vizhub.ai) and our workflow using several
real-world use cases.