---
layout: publication
title: 'Prompt Learning For Multi-label Code Smell Detection: A Promising Approach'
authors: Liu et al.
conference: Software Quality Journal
year: 2024
bibkey: liu2024prompt
citations: 59
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.10398'}]
tags: [Prompting, RAG, Reinforcement Learning]
---
Code smells indicate the potential problems of software quality so that
developers can identify refactoring opportunities by detecting code smells.
State-of-the-art approaches leverage heuristics, machine learning, and deep
learning to detect code smells. However, existing approaches have not fully
explored the potential of large language models (LLMs). In this paper, we
propose \textit\{PromptSmell\}, a novel approach based on prompt learning for
detecting multi-label code smell. Firstly, code snippets are acquired by
traversing abstract syntax trees. Combined code snippets with natural language
prompts and mask tokens, \textit\{PromptSmell\} constructs the input of LLMs.
Secondly, to detect multi-label code smell, we leverage a label combination
approach by converting a multi-label problem into a multi-classification
problem. A customized answer space is added to the word list of pre-trained
language models, and the probability distribution of intermediate answers is
obtained by predicting the words at the mask positions. Finally, the
intermediate answers are mapped to the target class labels by a verbalizer as
the final classification result. We evaluate the effectiveness of
\textit\{PromptSmell\} by answering six research questions. The experimental
results demonstrate that \textit\{PromptSmell\} obtains an improvement of 11.17%
in \\(precision_\{w\}\\) and 7.4% in \\(F1_\{w\}\\) compared to existing approaches.