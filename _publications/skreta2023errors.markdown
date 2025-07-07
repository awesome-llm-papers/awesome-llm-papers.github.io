---
layout: publication
title: 'Errors Are Useful Prompts: Instruction Guided Task Programming With Verifier-assisted
  Iterative Prompting'
authors: Marta Skreta et al.
conference: Arxiv
year: 2023
citations: 16
bibkey: skreta2023errors
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.14100'}]
tags: [Prompting]
---
Generating low-level robot task plans from high-level natural language
instructions remains a challenging problem. Although large language models have
shown promising results in generating plans, the accuracy of the output remains
unverified. Furthermore, the lack of domain-specific language data poses a
limitation on the applicability of these models. In this paper, we propose
CLAIRIFY, a novel approach that combines automatic iterative prompting with
program verification to ensure programs written in data-scarce domain-specific
language are syntactically valid and incorporate environment constraints. Our
approach provides effective guidance to the language model on generating
structured-like task plans by incorporating any errors as feedback, while the
verifier ensures the syntactic accuracy of the generated plans. We demonstrate
the effectiveness of CLAIRIFY in planning chemistry experiments by achieving
state-of-the-art results. We also show that the generated plans can be executed
on a real robot by integrating them with a task and motion planner.