---
layout: publication
title: 'Lean-github: Compiling Github LEAN Repositories For A Versatile LEAN Prover'
authors: Wu et al.
conference: Proceedings of the 11th Working Conference on Mining Software Repositories
year: 2024
bibkey: wu2024lean
citations: 95
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2407.17227'}]
tags: [Fine Tuning, Training Techniques, Evaluation, Datasets]
---
Recently, large language models have presented promising results in aiding
formal mathematical reasoning. However, their performance is restricted due to
the scarcity of formal theorem-proving data, which requires additional effort
to be extracted from raw formal language corpora. Meanwhile, a significant
amount of human-written formal language corpora remains underutilized. To
address this issue, we propose LEAN-GitHub, a dataset consisting of large-scale
formal data extracted from almost all Lean 4 repositories on GitHub. After
fine-tuning InternLM-math-plus on this dataset, our model achieved accuracies
of 48.8% with a single pass and 54.5% with 64 passes on the Lean 4 miniF2F
test, surpassing state-of-the-art method at 52%. And it also achieves
state-of-the-art on two other Lean 4 benchmarks (ProofNet and Putnam) targeting
different fields/levels of math. These results demonstrate that our proposed
dataset is beneficial for formal reasoning on a wide range of math topics. We
open-source our model at https://GitHub. com/InternLM/InternLM-Math and our
data at https://huggingface.co/ datasets/InternLM/Lean-GitHub