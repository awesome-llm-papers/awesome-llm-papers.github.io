---
layout: publication
title: Locating And Editing Factual Associations In GPT
authors: Kevin Meng, David Bau, Alex Andonian, Yonatan Belinkov
conference: Arxiv
year: 2022
bibkey: meng2022locating
citations: 154
additional_links: [{name: Code, url: 'https://rome.baulab.info/'}, {name: Paper, url: 'https://arxiv.org/abs/2202.05262'}]
tags: ["Datasets", "Evaluation", "Model Architecture"]
short_authors: Meng et al.
---
We analyze the storage and recall of factual associations in autoregressive
transformer language models, finding evidence that these associations
correspond to localized, directly-editable computations. We first develop a
causal intervention for identifying neuron activations that are decisive in a
model's factual predictions. This reveals a distinct set of steps in
middle-layer feed-forward modules that mediate factual predictions while
processing subject tokens. To test our hypothesis that these computations
correspond to factual association recall, we modify feed-forward weights to
update specific factual associations using Rank-One Model Editing (ROME). We
find that ROME is effective on a standard zero-shot relation extraction (zsRE)
model-editing task, comparable to existing methods. To perform a more sensitive
evaluation, we also evaluate ROME on a new dataset of counterfactual
assertions, on which it simultaneously maintains both specificity and
generalization, whereas other methods sacrifice one or another. Our results
confirm an important role for mid-layer feed-forward modules in storing factual
associations and suggest that direct manipulation of computational mechanisms
may be a feasible approach for model editing. The code, dataset,
visualizations, and an interactive demo notebook are available at
https://rome.baulab.info/