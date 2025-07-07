---
layout: publication
title: A Token-level Reference-free Hallucination Detection Benchmark For Free-form
  Text Generation
authors: Tianyu Liu et al.
conference: Arxiv
year: 2021
citations: 21
bibkey: liu2021token
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.08704'}]
tags: [GPT, Model Architecture, Applications, Language Modeling, ACL]
---
Large pretrained generative models like GPT-3 often suffer from hallucinating
non-existent or incorrect content, which undermines their potential merits in
real applications. Existing work usually attempts to detect these
hallucinations based on a corresponding oracle reference at a sentence or
document level. However ground-truth references may not be readily available
for many free-form text generation applications, and sentence- or
document-level detection may fail to provide the fine-grained signals that
would prevent fallacious content in real time. As a first step to addressing
these issues, we propose a novel token-level, reference-free hallucination
detection task and an associated annotated dataset named HaDes (HAllucination
DEtection dataSet). To create this dataset, we first perturb a large number of
text segments extracted from English language Wikipedia, and then verify these
with crowd-sourced annotations. To mitigate label imbalance during annotation,
we utilize an iterative model-in-loop strategy. We conduct comprehensive data
analyses and create multiple baseline models.