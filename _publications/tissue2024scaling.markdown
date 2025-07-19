---
layout: publication
title: Scaling Law With Learning Rate Annealing
authors: Tissue Howe, Wang Venus, Wang Lu
conference: Physical Review Letters
year: 2024
bibkey: tissue2024scaling
citations: 54
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2408.11029'}]
tags: [Interpretability And Explainability, Scaling Laws, Training Techniques, Model
    Architecture, Efficiency And Optimization, Reinforcement Learning, Large Scale
    Training]
---
We find that the cross-entropy loss curves of neural language models
empirically adhere to a scaling law with learning rate (LR) annealing over
training steps: $\\(L(s) = L_0 + A\cdot S_1^\{-\alpha\} - C\cdot S_2,\\)\\( where
\\)L(s)\\( is the validation loss at step \\)s\\(, \\)S_1\\( is the area under the LR
curve, \\)S_2\\( is the LR annealing area, and \\)L_0\\(, \\)A\\(, \\)C\\(, \\)\alpha$ are
constant parameters. This formulation takes into account two factors: (1)
power-law scaling over data size, and (2) the additional loss reduction during
LR annealing. Therefore, this formulation can describe the full loss curve at
each step, rather than the single loss point at the end of training. Applying
the scaling law with LR annealing and fitting only one or two training curves,
we can accurately predict the loss at any given step across any learning rate
scheduler (LRS). This approach significantly reduces computational cost in
formulating scaling laws while providing more accuracy and expressiveness for
training dynamics. Extensive experiments demonstrate that our findings hold
across a range of hyper-parameters and model architectures, and our equation
can extend to scaling effect of model sizes. Moreover, our formulation provides
accurate theoretical verification and explanation for empirical results
observed in numerous previous studies, particularly those focusing on LR
schedule and annealing. We believe that this work is promising to enhance the
understanding of LLM training dynamics while greatly democratizing scaling
laws, and it can guide researchers in refining training strategies (e.g.
critical LRS) for further LLMs.