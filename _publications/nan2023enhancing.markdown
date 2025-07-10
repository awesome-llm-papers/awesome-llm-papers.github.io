---
layout: publication
title: 'Enhancing Few-shot Text-to-sql Capabilities Of Large Language Models: A Study
  On Prompt Design Strategies'
authors: Linyong Nan et al.
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2023'
year: 2023
citations: 15
bibkey: nan2023enhancing
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.12586'}]
tags: [In-Context Learning, Few-Shot, Prompting, RAG]
---
In-context learning (ICL) has emerged as a new approach to various natural
language processing tasks, utilizing large language models (LLMs) to make
predictions based on context that has been supplemented with a few examples or
task-specific instructions. In this paper, we aim to extend this method to
question answering tasks that utilize structured knowledge sources, and improve
Text-to-SQL systems by exploring various prompt design strategies for employing
LLMs. We conduct a systematic investigation into different demonstration
selection methods and optimal instruction formats for prompting LLMs in the
Text-to-SQL task. Our approach involves leveraging the syntactic structure of
an example's SQL query to retrieve demonstrations, and we demonstrate that
pursuing both diversity and similarity in demonstration selection leads to
enhanced performance. Furthermore, we show that LLMs benefit from
database-related knowledge augmentations. Our most effective strategy
outperforms the state-of-the-art system by 2.5 points (Execution Accuracy) and
the best fine-tuned system by 5.1 points on the Spider dataset. These results
highlight the effectiveness of our approach in adapting LLMs to the Text-to-SQL
task, and we present an analysis of the factors contributing to the success of
our strategy.