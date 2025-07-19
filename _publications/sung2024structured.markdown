---
layout: publication
title: Structured List-grounded Question Answering
authors: Sung et al.
conference: 2016 IEEE Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: sung2024structured
citations: 372
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.03950'}]
tags: [RAG, GPT, Evaluation, CVPR, Model Architecture, Reinforcement Learning, Datasets]
---
Document-grounded dialogue systems aim to answer user queries by leveraging
external information. Previous studies have mainly focused on handling
free-form documents, often overlooking structured data such as lists, which can
represent a range of nuanced semantic relations. Motivated by the observation
that even advanced language models like GPT-3.5 often miss semantic cues from
lists, this paper aims to enhance question answering (QA) systems for better
interpretation and use of structured lists. To this end, we introduce the
LIST2QA dataset, a novel benchmark to evaluate the ability of QA systems to
respond effectively using list information. This dataset is created from
unlabeled customer service documents using language models and model-based
filtering processes to enhance data quality, and can be used to fine-tune and
evaluate QA models. Apart from directly generating responses through fine-tuned
models, we further explore the explicit use of Intermediate Steps for Lists
(ISL), aligning list items with user backgrounds to better reflect how humans
interpret list items before generating responses. Our experimental results
demonstrate that models trained on LIST2QA with our ISL approach outperform
baselines across various metrics. Specifically, our fine-tuned Flan-T5-XL model
shows increases of 3.1% in ROUGE-L, 4.6% in correctness, 4.5% in faithfulness,
and 20.6% in completeness compared to models without applying filtering and the
proposed ISL method.