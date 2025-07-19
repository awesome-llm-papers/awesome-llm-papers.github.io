---
layout: publication
title: Towards Better Understanding Of In-context Learning Ability From In-context
  Uncertainty Quantification
authors: Liu et al.
conference: Lecture Notes in Computer Science
year: 2024
bibkey: liu2024towards
citations: 1457
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2405.15115'}]
tags: [Training Techniques, Prompting, Transformer, In Context Learning, Model Architecture]
---
Predicting simple function classes has been widely used as a testbed for
developing theory and understanding of the trained Transformer's in-context
learning (ICL) ability. In this paper, we revisit the training of Transformers
on linear regression tasks, and different from all the existing literature, we
consider a bi-objective prediction task of predicting both the conditional
expectation \\(\mathbb\{E\}[Y|X]\\) and the conditional variance Var\\((Y|X)\\). This
additional uncertainty quantification objective provides a handle to (i) better
design out-of-distribution experiments to distinguish ICL from in-weight
learning (IWL) and (ii) make a better separation between the algorithms with
and without using the prior information of the training distribution.
Theoretically, we show that the trained Transformer reaches near Bayes-optimum,
suggesting the usage of the information of the training distribution. Our
method can be extended to other cases. Specifically, with the Transformer's
context window \\(S\\), we prove a generalization bound of
\\(\tilde\{\mathcal\{O\}\}(\sqrt\{\min\\{S, T\\}/(n T)\})\\) on \\(n\\) tasks with sequences of
length \\(T\\), providing sharper analysis compared to previous results of
\\(\tilde\{\mathcal\{O\}\}(\sqrt\{1/n\})\\). Empirically, we illustrate that while the
trained Transformer behaves as the Bayes-optimal solution as a natural
consequence of supervised training in distribution, it does not necessarily
perform a Bayesian inference when facing task shifts, in contrast to the
\textit\{equivalence\} between these two proposed in many existing literature. We
also demonstrate the trained Transformer's ICL ability over covariates shift
and prompt-length shift and interpret them as a generalization over a meta
distribution.