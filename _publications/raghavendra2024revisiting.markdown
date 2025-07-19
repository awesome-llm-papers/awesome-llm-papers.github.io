---
layout: publication
title: Revisiting The Superficial Alignment Hypothesis
authors: Raghavendra Mohit, Nath Vaskar, Hendryx Sean
conference: Journal of Fluid Mechanics
year: 2024
bibkey: raghavendra2024revisiting
citations: 69
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.03717'}]
tags: [Scaling Laws, RAG, Training Techniques, Evaluation, Efficiency And Optimization,
  Large Scale Training, Datasets]
---
The Superficial Alignment Hypothesis posits that almost all of a language
model's abilities and knowledge are learned during pre-training, while
post-training is about giving a model the right style and format. We re-examine
these claims by empirically studying the scaling behavior of post-training with
increasing finetuning examples and evaluating them using objective
task-specific standardized benchmarks. Through experiments with the Llama-3,
Mistral, and Llama-2 model families of multiple sizes, we observe that, similar
to the pre-training scaling laws, post-training task performance scales as a
power law against the number of finetuning examples. This power law
relationship holds across a broad array of capabilities, including mathematical
reasoning, coding, instruction following, and multihop-reasoning. In addition,
for tasks like math and multihop reasoning, we observe that a handful of
examples merely align the model stylistically but do not saturate performance
on the benchmarks. Model performance is instead correlated with its reasoning
ability and it improves significantly with more examples, illustrating the need
for holistic evaluation programs leveraging objective benchmarks in addition to
measurement of alignment to human preferences. We also observe that language
models are not necessarily limited to using knowledge learned during
pre-training. With appropriate post-training, a model's ability to integrate
new knowledge greatly improves on downstream tasks like multihop
question-answering. Taken together, these results shed new light on the
Superficial Alignment Hypothesis, suggesting that it is, at best, an
over-simplification.