---
layout: publication
title: 'Tree Of Thoughts: Deliberate Problem Solving With Large Language Models'
authors: Shunyu Yao et al.
conference: Arxiv
year: 2023
citations: 292
bibkey: yao2023tree
additional_links: [{name: Paper, url: 'http://arxiv.org/abs/2305.10601v2'}, {name: Code,
    url: 'https://github.com/princeton-nlp/tree-of-thought-llm'}]
tags: [GPT, Fine-Tuning, Tools, Has Code, Prompting, Model Architecture]
---
Language models are increasingly being deployed for general problem solving
across a wide range of tasks, but are still confined to token-level,
left-to-right decision-making processes during inference. This means they can
fall short in tasks that require exploration, strategic lookahead, or where
initial decisions play a pivotal role. To surmount these challenges, we
introduce a new framework for language model inference, Tree of Thoughts (ToT),
which generalizes over the popular Chain of Thought approach to prompting
language models, and enables exploration over coherent units of text (thoughts)
that serve as intermediate steps toward problem solving. ToT allows LMs to
perform deliberate decision making by considering multiple different reasoning
paths and self-evaluating choices to decide the next course of action, as well
as looking ahead or backtracking when necessary to make global choices. Our
experiments show that ToT significantly enhances language models'
problem-solving abilities on three novel tasks requiring non-trivial planning
or search: Game of 24, Creative Writing, and Mini Crosswords. For instance, in
Game of 24, while GPT-4 with chain-of-thought prompting only solved 4% of
tasks, our method achieved a success rate of 74%. Code repo with all prompts:
https://github.com/princeton-nlp/tree-of-thought-llm.