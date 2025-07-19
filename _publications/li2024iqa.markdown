---
layout: publication
title: 'IQA-EVAL: Automatic Evaluation Of Human-model Interactive Question Answering'
authors: Li et al.
conference: 2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition
year: 2024
bibkey: li2024iqa
citations: 166
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2408.13545'}]
tags: [GPT, Agentic, Tools, Evaluation, CVPR, Model Architecture]
---
To evaluate Large Language Models (LLMs) for question answering (QA),
traditional methods typically focus on assessing single-turn responses to given
questions. However, this approach doesn't capture the dynamic nature of
human-AI interactions, where humans actively seek information through
conversation. Recent works in human-computer interaction (HCI) have employed
human evaluators to conduct interactions and evaluations, but they are often
prohibitively expensive and time-consuming to scale. We introduce an automatic
evaluation framework IQA-EVAL to achieve Interactive Question Answering
Evaluations, more specifically, we introduce a LLM-based Evaluation Agent (LEA)
that can: (1) simulate human behaviors to generate interactions with IQA
models; (2) automatically evaluate the generated interactions. Moreover, we
propose assigning personas to LEAs to better simulate groups of real human
evaluators. We show that: (1) our evaluation framework with GPT-4 (or Claude)
as the backbone model achieves a high correlation with human evaluations on the
IQA task; (2) assigning personas to LEA to better represent the crowd further
significantly improves correlations. Finally, we use our automatic metric to
evaluate five recent representative LLMs with over 1000 questions from complex
and ambiguous question answering tasks, which comes with a substantial cost of
$5k if evaluated by humans.