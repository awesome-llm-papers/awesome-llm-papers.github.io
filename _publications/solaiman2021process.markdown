---
layout: publication
title: Process For Adapting Language Models To Society (PALMS) With Values-targeted
  Datasets
authors: Irene Solaiman, Christy Dennison
conference: Arxiv
year: 2021
bibkey: solaiman2021process
citations: 74
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2106.10328'}]
tags: ["Datasets", "Evaluation", "Fine-Tuning", "Model Architecture", "Training Techniques"]
short_authors: Irene Solaiman, Christy Dennison
---
Language models can generate harmful and biased outputs and exhibit
undesirable behavior according to a given cultural context. We propose a
Process for Adapting Language Models to Society (PALMS) with Values-Targeted
Datasets, an iterative process to significantly change model behavior by
crafting and fine-tuning on a dataset that reflects a predetermined set of
target values. We evaluate our process using three metrics: quantitative
metrics with human evaluations that score output adherence to a target value,
toxicity scoring on outputs; and qualitative metrics analyzing the most common
word associated with a given social category. Through each iteration, we add
additional training dataset examples based on observed shortcomings from
evaluations. PALMS performs significantly better on all metrics compared to
baseline and control models for a broad range of GPT-3 language model sizes
without compromising capability integrity. We find that the effectiveness of
PALMS increases with model size. We show that significantly adjusting language
model behavior is feasible with a small, hand-curated dataset.