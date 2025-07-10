---
layout: publication
title: Narrative Interpolation For Generating And Understanding Stories
authors: Su Wang, Greg Durrett, Katrin Erk
conference: Arxiv
year: 2020
citations: 24
bibkey: wang2020narrative
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2008.07466'}]
tags: [GPT, Model Architecture, Evaluation]
---
We propose a method for controlled narrative/story generation where we are
able to guide the model to produce coherent narratives with user-specified
target endings by interpolation: for example, we are told that Jim went hiking
and at the end Jim needed to be rescued, and we want the model to incrementally
generate steps along the way. The core of our method is an interpolation model
based on GPT-2 which conditions on a previous sentence and a next sentence in a
narrative and fills in the gap. Additionally, a reranker helps control for
coherence of the generated text. With human evaluation, we show that
ending-guided generation results in narratives which are coherent, faithful to
the given ending guide, and require less manual effort on the part of the human
guide writer than past approaches.