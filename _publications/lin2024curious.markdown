---
layout: publication
title: 'The Curious Case Of Class Accuracy Imbalance In Llms: Post-hoc Debiasing Via
  Nonlinear Integer Programming'
authors: Lin Ruixi, You Yang
conference: 50 Years of Integer Programming 1958-2008
year: 2024
bibkey: lin2024curious
citations: 94
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2405.07623'}]
tags: [Training Techniques, Prompting, Evaluation, Ethics And Bias, Efficiency And
    Optimization, Datasets]
---
Large language models (LLMs) are good knowledge bases but struggle to perform equally well for all classes in text classification. This paper investigates the case of class accuracy imbalance in LLMs, where deeply entangled pretraining biases and prompt-specific cues contribute to the imbalance. To overcome the difficulty in bias identification and inaccessibility of retraining, we post-hoc balance class accuracy using only output probabilities. This is enabled by reformulating debiasing as a combinatorial optimization problem. In details, we first motivate a post-hoc bias metric, the Contextual Oddity Bias (COBias), to quantify the over-/under-prediction (a tendency to over-predict some classes while under-predicting others) in LLMs. We then propose the Debiasing as Nonlinear Integer Programming (DNIP) method to reweight LLM output class probabilities towards minimizing COBias and max12 imizing overall accuracy, without being constrained by bias sources or updating LLM parameters. Since the DNIP model contains non-differentiable elements, we use simulated annealing to efficiently solve it. Evaluations on five LLMs across NLP classification benchmarks show that DNIP simultaneously achieves signifi16 cant COBias reduction (61% relative reduction) and accuracy improvement (18% relative increase) under different LLM prompting setups.