---
layout: publication
title: 'Gatenlp At Semeval-2025 Task 10: Hierarchical Three-step Prompting For Multilingual
  Narrative Classification'
authors: Singh Iknoor, Scarton Carolina, Bontcheva Kalina
conference: Proceedings of the 8th International Workshop on Semantic Evaluation (SemEval
  2014)
year: 2025
bibkey: singh2025gatenlp
citations: 173
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.22867'}]
tags: [Prompting, Evaluation, Reinforcement Learning, Security, Merging]
---
The proliferation of online news and the increasing spread of misinformation necessitate robust methods for automatic data analysis. Narrative classification is emerging as a important task, since identifying what is being said online is critical for fact-checkers, policy markers and other professionals working on information studies. This paper presents our approach to SemEval 2025 Task 10 Subtask 2, which aims to classify news articles into a pre-defined two-level taxonomy of main narratives and sub-narratives across multiple languages.
  We propose Hierarchical Three-Step Prompting (H3Prompt) for multilingual narrative classification. Our methodology follows a three-step Large Language Model (LLM) prompting strategy, where the model first categorises an article into one of two domains (Ukraine-Russia War or Climate Change), then identifies the most relevant main narratives, and finally assigns sub-narratives. Our approach secured the top position on the English test set among 28 competing teams worldwide. The code is available at https://github.com/GateNLP/H3Prompt.