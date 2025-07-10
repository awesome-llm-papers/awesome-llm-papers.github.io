---
layout: publication
title: Does Fine-tuning Llms On New Knowledge Encourage Hallucinations?
authors: Zorik Gekhman et al.
conference: Proceedings of the 2024 Conference on Empirical Methods in Natural Language
  Processing
year: 2024
citations: 20
bibkey: gekhman2024does
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2405.05904'}]
tags: [Fine-Tuning, RAG, Reinforcement Learning, Pre-Training, Training Techniques]
---
When large language models are aligned via supervised fine-tuning, they may
encounter new factual information that was not acquired through pre-training.
It is often conjectured that this can teach the model the behavior of
hallucinating factually incorrect responses, as the model is trained to
generate facts that are not grounded in its pre-existing knowledge. In this
work, we study the impact of such exposure to new knowledge on the capability
of the fine-tuned model to utilize its pre-existing knowledge. To this end, we
design a controlled setup, focused on closed-book QA, where we vary the
proportion of the fine-tuning examples that introduce new knowledge. We
demonstrate that large language models struggle to acquire new factual
knowledge through fine-tuning, as fine-tuning examples that introduce new
knowledge are learned significantly slower than those consistent with the
model's knowledge. However, we also find that as the examples with new
knowledge are eventually learned, they linearly increase the model's tendency
to hallucinate. Taken together, our results highlight the risk in introducing
new factual knowledge through fine-tuning, and support the view that large
language models mostly acquire factual knowledge through pre-training, whereas
fine-tuning teaches them to use it more efficiently.