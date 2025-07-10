---
layout: publication
title: Unqovering Stereotyping Biases Via Underspecified Questions
authors: Tao Li, Tushar Khot, Daniel Khashabi, Ashish Sabharwal, Vivek Srikumar
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2020'
year: 2020
citations: 18
bibkey: li2020unqovering
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.02428'}]
tags: [Model Architecture, Ethics and Bias, Transformer, Fine-Tuning, Tools, Reinforcement
    Learning, Training Techniques]
---
While language embeddings have been shown to have stereotyping biases, how
these biases affect downstream question answering (QA) models remains
unexplored. We present UNQOVER, a general framework to probe and quantify
biases through underspecified questions. We show that a naive use of model
scores can lead to incorrect bias estimates due to two forms of reasoning
errors: positional dependence and question independence. We design a formalism
that isolates the aforementioned errors. As case studies, we use this metric to
analyze four important classes of stereotypes: gender, nationality, ethnicity,
and religion. We probe five transformer-based QA models trained on two QA
datasets, along with their underlying language models. Our broad study reveals
that (1) all these models, with and without fine-tuning, have notable
stereotyping biases in these classes; (2) larger models often have higher bias;
and (3) the effect of fine-tuning on bias varies strongly with the dataset and
the model size.