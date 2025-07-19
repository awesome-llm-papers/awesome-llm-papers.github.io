---
layout: publication
title: On Explaining (large) Language Models For Code Using Global Code-based Explanations
authors: Palacio et al.
conference: Proceedings of the 2022 ACM Conference on International Computing Education
  Research - Volume 1
year: 2025
bibkey: palacio2025explaining
citations: 279
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.16771'}]
tags: [Interpretability And Explainability, Attention Mechanism, Evaluation, Model
    Architecture, Fine Tuning, Datasets, LLM For Code]
---
In recent years, Language Models for Code (LLM4Code) have significantly
changed the landscape of software engineering (SE) on downstream tasks, such as
code generation, by making software development more efficient. Therefore, a
growing interest has emerged in further evaluating these Language Models to
homogenize the quality assessment of generated code. As the current evaluation
process can significantly overreact on accuracy-based metrics, practitioners
often seek methods to interpret LLM4Code outputs beyond canonical benchmarks.
While the majority of research reports on code generation effectiveness in
terms of expected ground truth, scant attention has been paid to LLMs'
explanations. In essence, the decision-making process to generate code is hard
to interpret. To bridge this evaluation gap, we introduce code rationales
(Code\\(Q\\)), a technique with rigorous mathematical underpinning, to identify
subsets of tokens that can explain individual code predictions. We conducted a
thorough Exploratory Analysis to demonstrate the method's applicability and a
User Study to understand the usability of code-based explanations. Our
evaluation demonstrates that Code\\(Q\\) is a powerful interpretability method to
explain how (less) meaningful input concepts (i.e., natural language particle
`at') highly impact output generation. Moreover, participants of this study
highlighted Code\\(Q\\)'s ability to show a causal relationship between the input
and output of the model with readable and informative explanations on code
completion and test generation tasks. Additionally, Code\\(Q\\) also helps to
uncover model rationale, facilitating comparison with a human rationale to
promote a fair level of trust and distrust in the model.