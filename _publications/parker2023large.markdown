---
layout: publication
title: A Large Language Model Approach To Educational Survey Feedback Analysis
authors: Michael J. Parker, Caitlin Anderson, Claire Stone, Yearim Oh
conference: International Journal of Artificial Intelligence in Education
year: 2023
citations: 16
bibkey: parker2023large
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2309.17447'}]
tags: [Model Architecture, GPT, Fine-Tuning, Applications, Survey Paper, Reinforcement
    Learning, Prompting, Training Techniques]
---
This paper assesses the potential for the large language models (LLMs) GPT-4
and GPT-3.5 to aid in deriving insight from education feedback surveys.
Exploration of LLM use cases in education has focused on teaching and learning,
with less exploration of capabilities in education feedback analysis. Survey
analysis in education involves goals such as finding gaps in curricula or
evaluating teachers, often requiring time-consuming manual processing of
textual responses. LLMs have the potential to provide a flexible means of
achieving these goals without specialized machine learning models or
fine-tuning. We demonstrate a versatile approach to such goals by treating them
as sequences of natural language processing (NLP) tasks including
classification (multi-label, multi-class, and binary), extraction, thematic
analysis, and sentiment analysis, each performed by LLM. We apply these
workflows to a real-world dataset of 2500 end-of-course survey comments from
biomedical science courses, and evaluate a zero-shot approach (i.e., requiring
no examples or labeled training data) across all tasks, reflecting education
settings, where labeled data is often scarce. By applying effective prompting
practices, we achieve human-level performance on multiple tasks with GPT-4,
enabling workflows necessary to achieve typical goals. We also show the
potential of inspecting LLMs' chain-of-thought (CoT) reasoning for providing
insight that may foster confidence in practice. Moreover, this study features
development of a versatile set of classification categories, suitable for
various course types (online, hybrid, or in-person) and amenable to
customization. Our results suggest that LLMs can be used to derive a range of
insights from survey text.