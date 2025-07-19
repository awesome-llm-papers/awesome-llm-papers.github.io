---
layout: publication
title: 'Fast Yet Safe: Early-exiting With Risk Control'
authors: Jazbec et al.
conference: 2016 23rd International Conference on Pattern Recognition (ICPR)
year: 2024
bibkey: jazbec2024fast
citations: 748
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2405.20915'}]
tags: [Tools, Reinforcement Learning]
---
Scaling machine learning models significantly improves their performance.
However, such gains come at the cost of inference being slow and
resource-intensive. Early-exit neural networks (EENNs) offer a promising
solution: they accelerate inference by allowing intermediate layers to exit and
produce a prediction early. Yet a fundamental issue with EENNs is how to
determine when to exit without severely degrading performance. In other words,
when is it 'safe' for an EENN to go 'fast'? To address this issue, we
investigate how to adapt frameworks of risk control to EENNs. Risk control
offers a distribution-free, post-hoc solution that tunes the EENN's exiting
mechanism so that exits only occur when the output is of sufficient quality. We
empirically validate our insights on a range of vision and language tasks,
demonstrating that risk control can produce substantial computational savings,
all the while preserving user-specified performance goals.