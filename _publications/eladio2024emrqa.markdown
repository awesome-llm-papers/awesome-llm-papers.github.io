---
layout: publication
title: 'Emrqa-msquad: A Medical Dataset Structured With The Squad V2.0 Framework,
  Enriched With Emrqa Medical Information'
authors: Eladio Jimenez, Wu Hao
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2024
bibkey: eladio2024emrqa
citations: 71
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2404.12050'}]
tags: [Training Techniques, EMNLP, Tools, BERT, Model Architecture, Security, Fine
    Tuning, Datasets]
---
Machine Reading Comprehension (MRC) holds a pivotal role in shaping Medical
Question Answering Systems (QAS) and transforming the landscape of accessing
and applying medical information. However, the inherent challenges in the
medical field, such as complex terminology and question ambiguity, necessitate
innovative solutions. One key solution involves integrating specialized medical
datasets and creating dedicated datasets. This strategic approach enhances the
accuracy of QAS, contributing to advancements in clinical decision-making and
medical research. To address the intricacies of medical terminology, a
specialized dataset was integrated, exemplified by a novel Span extraction
dataset derived from emrQA but restructured into 163,695 questions and 4,136
manually obtained answers, this new dataset was called emrQA-msquad dataset.
Additionally, for ambiguous questions, a dedicated medical dataset for the Span
extraction task was introduced, reinforcing the system's robustness. The
fine-tuning of models such as BERT, RoBERTa, and Tiny RoBERTa for medical
contexts significantly improved response accuracy within the F1-score range of
0.75 to 1.00 from 10.1% to 37.4%, 18.7% to 44.7% and 16.0% to 46.8%,
respectively. Finally, emrQA-msquad dataset is publicy available at
https://huggingface.co/datasets/Eladio/emrqa-msquad.