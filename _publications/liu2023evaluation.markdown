---
layout: publication
title: Evaluation Of Human-model Prediction Difference On The Internet Scale Of Data
authors: Liu et al.
conference: Proceedings of the 16th international conference on World Wide Web
year: 2023
bibkey: liu2023evaluation
citations: 69
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2312.03291'}]
tags: [Reinforcement Learning, Evaluation, Datasets]
---
Evaluating models on datasets often fails to capture their behavior when
faced with unexpected and diverse types of inputs. It would be beneficial if we
could evaluate the difference between human annotation and model prediction for
an internet number of inputs, or more generally, for an input space that
enumeration is computationally impractical. Traditional model evaluation
methods rely on precision and recall (PR) as metrics, which are typically
estimated by comparing human annotations with model predictions on a specific
dataset. This is feasible because enumerating thousands of test inputs is
manageable. However, estimating PR across a large input space is challenging
because enumeration becomes computationally infeasible. We propose OmniInput, a
novel approach to evaluate and compare NNs by the PR of an input space.
OmniInput is distinctive from previous works as its estimated PR reflects the
estimation of the differences between human annotation and model prediction in
the input space which is usually too huge to be enumerated. We empirically
validate our method within an enumerable input space, and our experiments
demonstrate that OmniInput can effectively estimate and compare precision and
recall for (large) language models within a broad input space that is not
enumerable.