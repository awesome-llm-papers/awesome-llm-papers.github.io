---
layout: publication
title: A Methodology For Explainable Large Language Models With Integrated Gradients
  And Linguistic Analysis In Text Classification
authors: Ribeiro et al.
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2023'
year: 2024
bibkey: ribeiro2024methodology
citations: 75
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.00250'}]
tags: [Model Architecture, Interpretability And Explainability, Tools, BERT, ACL,
  EMNLP, RAG, Transformer, Datasets, Reinforcement Learning]
---
Neurological disorders that affect speech production, such as Alzheimer's
Disease (AD), significantly impact the lives of both patients and caregivers,
whether through social, psycho-emotional effects or other aspects not yet fully
understood. Recent advancements in Large Language Model (LLM) architectures
have developed many tools to identify representative features of neurological
disorders through spontaneous speech. However, LLMs typically lack
interpretability, meaning they do not provide clear and specific reasons for
their decisions. Therefore, there is a need for methods capable of identifying
the representative features of neurological disorders in speech and explaining
clearly why these features are relevant. This paper presents an explainable LLM
method, named SLIME (Statistical and Linguistic Insights for Model
Explanation), capable of identifying lexical components representative of AD
and indicating which components are most important for the LLM's decision. In
developing this method, we used an English-language dataset consisting of
transcriptions from the Cookie Theft picture description task. The LLM
Bidirectional Encoder Representations from Transformers (BERT) classified the
textual descriptions as either AD or control groups. To identify representative
lexical features and determine which are most relevant to the model's decision,
we used a pipeline involving Integrated Gradients (IG), Linguistic Inquiry and
Word Count (LIWC), and statistical analysis. Our method demonstrates that BERT
leverages lexical components that reflect a reduction in social references in
AD and identifies which further improve the LLM's accuracy. Thus, we provide an
explainability tool that enhances confidence in applying LLMs to neurological
clinical contexts, particularly in the study of neurodegeneration.