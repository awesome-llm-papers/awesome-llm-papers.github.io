---
layout: publication
title: Improving Large Language Models For Clinical Named Entity Recognition Via Prompt
  Engineering
authors: Hu et al.
conference: Journal of the American Medical Informatics Association
year: 2023
bibkey: hu2023improving
citations: 118
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.16416'}]
tags: [Datasets, Training Techniques, GPT, Alt, Prompting, Tools, BERT, Model Architecture,
  Few Shot, Applications, Responsible AI]
---
Objective: This study quantifies the capabilities of GPT-3.5 and GPT-4 for
clinical named entity recognition (NER) tasks and proposes task-specific
prompts to improve their performance. Materials and Methods: We evaluated these
models on two clinical NER tasks: (1) to extract medical problems, treatments,
and tests from clinical notes in the MTSamples corpus, following the 2010 i2b2
concept extraction shared task, and (2) identifying nervous system
disorder-related adverse events from safety reports in the vaccine adverse
event reporting system (VAERS). To improve the GPT models' performance, we
developed a clinical task-specific prompt framework that includes (1) baseline
prompts with task description and format specification, (2) annotation
guideline-based prompts, (3) error analysis-based instructions, and (4)
annotated samples for few-shot learning. We assessed each prompt's
effectiveness and compared the models to BioClinicalBERT. Results: Using
baseline prompts, GPT-3.5 and GPT-4 achieved relaxed F1 scores of 0.634, 0.804
for MTSamples, and 0.301, 0.593 for VAERS. Additional prompt components
consistently improved model performance. When all four components were used,
GPT-3.5 and GPT-4 achieved relaxed F1 socres of 0.794, 0.861 for MTSamples and
0.676, 0.736 for VAERS, demonstrating the effectiveness of our prompt
framework. Although these results trail BioClinicalBERT (F1 of 0.901 for the
MTSamples dataset and 0.802 for the VAERS), it is very promising considering
few training samples are needed. Conclusion: While direct application of GPT
models to clinical NER tasks falls short of optimal performance, our
task-specific prompt framework, incorporating medical knowledge and training
samples, significantly enhances GPT models' feasibility for potential clinical
applications.