---
layout: publication
title: 'Language Models Are Greedy Reasoners: A Systematic Formal Analysis Of Chain-of-thought'
authors: Abulhair Saparov, He He
conference: Arxiv
year: 2022
citations: 34
bibkey: saparov2022language
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2210.01240'}]
tags: [Model Architecture, Fine-Tuning, Reinforcement Learning, Prompting, GPT, Evaluation]
---
Large language models (LLMs) have shown remarkable reasoning capabilities
given chain-of-thought prompts (examples with intermediate reasoning steps).
Existing benchmarks measure reasoning ability indirectly, by evaluating
accuracy on downstream tasks such as mathematical reasoning. However, it is
unclear how these models obtain the answers and whether they rely on simple
heuristics rather than the generated chain-of-thought. To enable systematic
exploration of the reasoning ability of LLMs, we present a new synthetic
question-answering dataset called PrOntoQA, where each example is generated
from a synthetic world model represented in first-order logic. This allows us
to parse the generated chain-of-thought into symbolic proofs for formal
analysis. Our analysis on InstructGPT and GPT-3 shows that LLMs are quite
capable of making correct individual deduction steps, and so are generally
capable of reasoning, even in fictional contexts. However, they have difficulty
with proof planning: When multiple valid deduction steps are available, they
are not able to systematically explore the different options.