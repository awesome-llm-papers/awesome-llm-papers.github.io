---
layout: publication
title: Boosting Theory-of-mind Performance In Large Language Models Via Prompting
authors: Shima Rahimi Moghaddam, Christopher J. Honey
conference: Arxiv
year: 2023
citations: 29
bibkey: moghaddam2023boosting
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2304.11490'}]
tags: [Model Architecture, Reinforcement Learning, In-Context Learning, Prompting,
  Agentic, GPT, Evaluation]
---
Large language models (LLMs) excel in many tasks in 2023, but they still face
challenges in complex reasoning. Theory-of-mind (ToM) tasks, which require
understanding agents' beliefs, goals, and mental states, are essential for
common-sense reasoning involving humans, making it crucial to enhance LLM
performance in this area. This study measures the ToM performance of GPT-4 and
three GPT-3.5 variants (Davinci-2, Davinci-3, GPT-3.5-Turbo), and investigates
the effectiveness of in-context learning in improving their ToM comprehension.
We evaluated prompts featuring two-shot chain of thought reasoning and
step-by-step thinking instructions. We found that LLMs trained with
Reinforcement Learning from Human Feedback (RLHF) (all models excluding
Davinci-2) improved their ToM accuracy via in-context learning. GPT-4 performed
best in zero-shot settings, reaching nearly 80% ToM accuracy, but still fell
short of the 87% human accuracy on the test set. However, when supplied with
prompts for in-context learning, all RLHF-trained LLMs exceeded 80% ToM
accuracy, with GPT-4 reaching 100%. These results demonstrate that appropriate
prompting enhances LLM ToM reasoning, and they underscore the context-dependent
nature of LLM cognitive capacities.