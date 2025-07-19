---
layout: publication
title: 'Beads: Bias Evaluation Across Domains'
authors: Raza Shaina, Rahman Mizanur, Zhang Michael R.
conference: Genome Biology and Evolution
year: 2024
bibkey: raza2024beads
citations: 197
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2406.04220'}]
tags: [Datasets, RAG, Training Techniques, GPT, Evaluation, Ethics And Bias, Model
    Architecture, Reinforcement Learning, Applications, Fine Tuning, Responsible AI]
---
Recent advancements in large language models (LLMs) have significantly improved natural language processing (NLP) applications. However, these models often inherit biases from their training data. While several datasets exist for bias detection, most are limited to one or two NLP tasks, typically classification or evaluation, and lack comprehensive coverage across a broader range of tasks. To address this gap, we introduce the Bias Evaluations Across Domains (BEADs) dataset, designed to support a wide range of NLP tasks, including text classification, token classification, bias quantification, and benign language generation. A key contribution of this work is the gold-standard annotation provided by GPT-4 for scalability, with expert verification to ensure high reliability. BEADs can be used for both fine-tuning models (for classification and generation tasks) and evaluating LLM behavior. Our findings show that BEADs effectively surfaces various biases during model fine-tuning and helps reduce biases in language generation tasks while maintaining output quality. The dataset also highlights prevalent demographic biases in LLMs during evaluation. We release BEADs as a practical resource for detecting and mitigating bias across domains, supporting the development of responsible AI systems. Project: https://vectorinstitute.github.io/BEAD/ Data: https://huggingface.co/datasets/shainar/BEAD