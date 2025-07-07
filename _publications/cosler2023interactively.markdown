---
layout: publication
title: 'Nl2spec: Interactively Translating Unstructured Natural Language To Temporal
  Logics With Large Language Models'
authors: Matthias Cosler, Christopher Hahn, Daniel Mendoza, Frederik Schmitt, Caroline
  Trippel
conference: Arxiv
year: 2023
citations: 42
bibkey: cosler2023interactively
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.04864'}]
tags: [RAG, Tools]
---
A rigorous formalization of desired system requirements is indispensable when
performing any verification task. This often limits the application of
verification techniques, as writing formal specifications is an error-prone and
time-consuming manual task. To facilitate this, we present nl2spec, a framework
for applying Large Language Models (LLMs) to derive formal specifications (in
temporal logics) from unstructured natural language. In particular, we
introduce a new methodology to detect and resolve the inherent ambiguity of
system requirements in natural language: we utilize LLMs to map subformulas of
the formalization back to the corresponding natural language fragments of the
input. Users iteratively add, delete, and edit these sub-translations to amend
erroneous formalizations, which is easier than manually redrafting the entire
formalization. The framework is agnostic to specific application domains and
can be extended to similar specification languages and new neural models. We
perform a user study to obtain a challenging dataset, which we use to run
experiments on the quality of translations. We provide an open-source
implementation, including a web-based frontend.