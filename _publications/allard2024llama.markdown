---
layout: publication
title: 'Llama-sciq: An Educational Chatbot For Answering Science MCQ'
authors: Allard et al.
conference: Advances in Intelligent Systems and Computing
year: 2024
bibkey: allard2024llama
citations: 59
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2409.16779'}]
tags: [RAG, Training Techniques, Evaluation, Efficiency And Optimization, Reinforcement
    Learning, Fine Tuning, Quantization, Datasets]
---
Large Language Models (LLMs) often struggle with tasks requiring mathematical
reasoning, particularly multiple-choice questions (MCQs). To address this
issue, we developed LLaMa-SciQ, an educational chatbot designed to assist
college students in solving and understanding MCQs in STEM fields. We begin by
fine-tuning and aligning the models to human preferences. After comparing the
performance of Mistral-7B and LLaMa-8B, we selected the latter as the base
model due to its higher evaluation accuracy. To further enhance accuracy, we
implement Retrieval-Augmented Generation (RAG) and apply quantization to
compress the model, reducing inference time and increasing accessibility for
students. For mathematical reasoning, LLaMa-SciQ achieved 74.5% accuracy on the
GSM8k dataset and 30% on the MATH dataset. However, RAG does not improve
performance and even reduces it, likely due to retriever issues or the model's
unfamiliarity with context. Despite this, the quantized model shows only a 5%
loss in performance, demonstrating significant efficiency improvements.