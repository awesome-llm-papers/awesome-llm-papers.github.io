---
layout: publication
title: 'Distilling Large Language Models For Biomedical Knowledge Extraction: A Case
  Study On Adverse Drug Events'
authors: Gu et al.
conference: BMC Bioinformatics
year: 2023
bibkey: gu2023distilling
citations: 55
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2307.06439'}]
tags: [Training Techniques, Distillation, GPT, Alt, Evaluation, BERT, Model Architecture,
  Efficiency And Optimization, Applications]
---
Large language models (LLMs), such as GPT-4, have demonstrated remarkable
capabilities across a wide range of tasks, including health applications. In
this paper, we study how LLMs can be used to scale biomedical knowledge
curation. We find that while LLMs already possess decent competency in
structuring biomedical text, by distillation into a task-specific student model
through self-supervised learning, substantial gains can be attained over
out-of-box LLMs, with additional advantages such as cost, efficiency, and
white-box model access.
  We conduct a case study on adverse drug event (ADE) extraction, which is an
important area for improving care. On standard ADE extraction evaluation, a
GPT-3.5 distilled PubMedBERT model attained comparable accuracy as supervised
state-of-the-art models without using any labeled data. Despite being over
1,000 times smaller, the distilled model outperformed its teacher GPT-3.5 by
over 6 absolute points in F1 and GPT-4 by over 5 absolute points.
  Ablation studies on distillation model choice (e.g., PubMedBERT vs BioGPT)
and ADE extraction architecture shed light on best practice for biomedical
knowledge extraction. Similar gains were attained by distillation for other
standard biomedical knowledge extraction tasks such as gene-disease
associations and protected health information, further illustrating the promise
of this approach.