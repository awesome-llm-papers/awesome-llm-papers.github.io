---
layout: publication
title: Debiasing Algorithm Through Model Adaptation
authors: "Limisiewicz Tomasz, Mare\u010Dek David, Musil Tom\xE1\u0161"
conference: Arxiv
year: 2023
bibkey: limisiewicz2023debiasing
citations: 68
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.18913'}]
tags: [Training Techniques, Evaluation, Ethics And Bias]
---
Large language models are becoming the go-to solution for the ever-growing
number of tasks. However, with growing capacity, models are prone to rely on
spurious correlations stemming from biases and stereotypes present in the
training data. This work proposes a novel method for detecting and mitigating
gender bias in language models. We perform causal analysis to identify
problematic model components and discover that mid-upper feed-forward layers
are most prone to convey bias. Based on the analysis results, we intervene in
the model by applying a linear projection to the weight matrices of these
layers. Our titular method, DAMA, significantly decreases bias as measured by
diverse metrics while maintaining the model's performance on downstream tasks.
We release code for our method and models, which retrain LLaMA's
state-of-the-art performance while being significantly less biased.