---
layout: publication
title: Open-ended Medical Visual Question Answering Through Prefix Tuning Of Language
  Models
authors: Tom Van Sonsbeek, Mohammad Mahdi Derakhshani, Ivona Najdenkoska, Cees G.
  M. Snoek, Marcel Worring
conference: Lecture Notes in Computer Science
year: 2023
citations: 27
bibkey: vansonsbeek2023open
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.05977'}]
tags: [Fine-Tuning, RAG, Reinforcement Learning, Prompting, Training Techniques, Evaluation]
---
Medical Visual Question Answering (VQA) is an important challenge, as it
would lead to faster and more accurate diagnoses and treatment decisions. Most
existing methods approach it as a multi-class classification problem, which
restricts the outcome to a predefined closed-set of curated answers. We focus
on open-ended VQA and motivated by the recent advances in language models
consider it as a generative task. Leveraging pre-trained language models, we
introduce a novel method particularly suited for small, domain-specific,
medical datasets. To properly communicate the medical images to the language
model, we develop a network that maps the extracted visual features to a set of
learnable tokens. Then, alongside the question, these learnable tokens directly
prompt the language model. We explore recent parameter-efficient fine-tuning
strategies for language models, which allow for resource- and data-efficient
fine-tuning. We evaluate our approach on the prime medical VQA benchmarks,
namely, Slake, OVQA and PathVQA. The results demonstrate that our approach
outperforms existing methods across various training settings while also being
computationally efficient.