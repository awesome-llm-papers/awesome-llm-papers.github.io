---
layout: publication
title: Applying Large Language Models And Chain-of-thought For Automatic Scoring
authors: Gyeong-geon Lee, Ehsan Latif, Xuansheng Wu, Ninghao Liu, Xiaoming Zhai
conference: 'Computers and Education: Artificial Intelligence'
year: 2023
citations: 45
bibkey: lee2023applying
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2312.03748'}]
tags: [Model Architecture, Few-Shot, Interpretability and Explainability, Tools, Reinforcement
    Learning, Prompting, GPT]
---
This study investigates the application of large language models (LLMs),
specifically GPT-3.5 and GPT-4, with Chain-of-Though (CoT) in the automatic
scoring of student-written responses to science assessments. We focused on
overcoming the challenges of accessibility, technical complexity, and lack of
explainability that have previously limited the use of artificial
intelligence-based automatic scoring tools among researchers and educators.
With a testing dataset comprising six assessment tasks (three binomial and
three trinomial) with 1,650 student responses, we employed six prompt
engineering strategies to automatically score student responses. The six
strategies combined zero-shot or few-shot learning with CoT, either alone or
alongside item stem and scoring rubrics. Results indicated that few-shot (acc =
.67) outperformed zero-shot learning (acc = .60), with 12.6% increase. CoT,
when used without item stem and scoring rubrics, did not significantly affect
scoring accuracy (acc = .60). However, CoT prompting paired with contextual
item stems and rubrics proved to be a significant contributor to scoring
accuracy (13.44% increase for zero-shot; 3.7% increase for few-shot). We found
a more balanced accuracy across different proficiency categories when CoT was
used with a scoring rubric, highlighting the importance of domain-specific
reasoning in enhancing the effectiveness of LLMs in scoring tasks. We also
found that GPT-4 demonstrated superior performance over GPT -3.5 in various
scoring tasks when combined with the single-call greedy sampling or ensemble
voting nucleus sampling strategy, showing 8.64% difference. Particularly, the
single-call greedy sampling strategy with GPT-4 outperformed other approaches.