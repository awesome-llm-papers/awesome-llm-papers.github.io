---
layout: publication
title: Have Your Text And Use It Too! End-to-end Neural Data-to-text Generation With
  Semantic Fidelity
authors: Hamza Harkous, Isabel Groves, Amir Saffari
conference: Proceedings of the 28th International Conference on Computational Linguistics
year: 2020
bibkey: harkous2020have
citations: 66
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.06577'}]
tags: ["COLING"]
short_authors: Hamza Harkous, Isabel Groves, Amir Saffari
---
End-to-end neural data-to-text (D2T) generation has recently emerged as an
alternative to pipeline-based architectures. However, it has faced challenges
in generalizing to new domains and generating semantically consistent text. In
this work, we present DataTuner, a neural, end-to-end data-to-text generation
system that makes minimal assumptions about the data representation and the
target domain. We take a two-stage generation-reranking approach, combining a
fine-tuned language model with a semantic fidelity classifier. Each of our
components is learnt end-to-end without the need for dataset-specific
heuristics, entity delexicalization, or post-processing. We show that DataTuner
achieves state of the art results on the automated metrics across four major
D2T datasets (LDC2017T10, WebNLG, ViGGO, and Cleaned E2E), with a fluency
assessed by human annotators nearing or exceeding the human-written reference
texts. We further demonstrate that the model-based semantic fidelity scorer in
DataTuner is a better assessment tool compared to traditional, heuristic-based
measures. Our generated text has a significantly better semantic fidelity than
the state of the art across all four datasets